# ADempiere Open-ID Connector

A connector to generic Open-ID services like Keycloak or Okta, this project is a temporary solution meanwhile is approved [this](https://github.com/adempiere/adempiere/pull/4284) pull request

## Requirements
- [JDK 11 or later](https://adoptium.net/)
- [Gradle 8.0.1 or later](https://gradle.org/install/)


### Packages Names
This is a little project to use the generic providers as library and just have one package `org.spin.authentication.services.addons.provider`


### Model Util class for core changes
The unique class for handle the generic connection is `org.spin.authentication.services.addons.provider.GenericAuthentication`

## Binary Project

You can get all binaries from github [here](https://central.sonatype.com/artifact/io.github.adempiere/adempiere-open-id-connector/1.0.0).

All contruction is from github actions


## Some XML's:

All dictionary changes are writing from XML and all XML's hare `xml/migration`


## How to add this library?

Is very easy.

- Gradle

```Java
implementation 'io.github.adempiere:adempiere-open-id-connector:1.0.0'
```

- SBT

```
libraryDependencies += "io.github.adempiere" % "adempiere-open-id-connector" % "1.0.0"
```

- Apache Maven

```
<dependency>
    <groupId>io.github.adempiere</groupId>
    <artifactId>adempiere-open-id-connector</artifactId>
    <version>1.0.0</version>
</dependency>
```