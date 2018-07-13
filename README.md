### ala-parent-pom [![BuildStatus](https://travis-ci.org/AtlasOfLivingAustralia/ala-parent-pom.svg?branch=master)](https://travis-ci.org/AtlasOfLivingAustralia/ala-parent-pom)

This is a Maven Parent POM file which manages versions for plugins and some common dependencies such as JUnit to remove complexity from ALA Maven projects.

## Deployment

Deployment of ala-parent-pom is to Sonatype OSSRH for staging, and then release once confirmed.

Deployment is performed using the following command:

```bash
mvn clean deploy -Psonatype-oss-release
```

## Usage

Use the following as the parent for a pom file to use this parent pom:

```xml
     <parent>
         <groupId>au.org.ala</groupId>
         <artifactId>ala-parent-pom</artifactId>
         <version>10</version>
     </parent>

```
