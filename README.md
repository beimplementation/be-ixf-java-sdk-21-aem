# be-ixf-java-sdk-21-aem
BrightEdge IXF Java SDK for AEM - JDK 21

## Introduction

This project is a simple Maven project that builds a JAR file for Brightedge IXF Java SDK (JDK 21) for AEM.

## Build

To generate a JAR file for SDK, run the following command

```bash
mvn -Dmaven.test.skip=true clean package --non-recursive
```

## Install

To install the JAR files into your local Maven repository and sign with GPG, run the following command

```bash
mvn -Dmaven.test.skip=true clean install
```

## Deployment

To deploy the JAR files into Maven repository, run the following command

```bash
mvn -Dmaven.test.skip=true clean deploy
```


## Contact

For any questions or support, please contact BrightEdge Implementation Team at be_implementation@brightedge.com.
