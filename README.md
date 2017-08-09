### ala-parent-pom [![BuildStatus](https://travis-ci.org/AtlasOfLivingAustralia/ala-parent-pom.svg?branch=master)](https://travis-ci.org/AtlasOfLivingAustralia/ala-parent-pom)

## Deployment

Deployment of ala-parent-pom is to Sonatype OSSRH for staging, and then release once confirmed.

Deployment is performed using the following command:

```
mvn clean deploy -Psonatype-oss-release
```

## Usage

Use the following as the parent for a pom file to use this parent pom:

```
     <parent>
         <groupId>au.org.ala</groupId>
         <artifactId>ala-parent-pom</artifactId>
         <version>5</version>
     </parent>

```
