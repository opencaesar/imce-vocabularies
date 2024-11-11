# IMCE Vocabularies

[![Build Status](https://github.com/opencaesar/imce-vocabularies/actions/workflows/ci.yml/badge.svg)](https://github.com/opencaesar/imce-vocabularies/actions/workflows/ci.yml)
[![Release](https://img.shields.io/github/v/release/opencaesar/imce-vocabularies?label=Release)](https://github.com/opencaesar/imce-vocabularies/releases/latest)
[![Documentation](https://img.shields.io/badge/Documentation-HTML-orange)](https://www.opencaesar.io/imce-vocabularies/) 

This is a set of IMCE vocabularies expressed in [OML](https://github.com/opencaesar/oml)

## Clone
```
  git clone https://github.com/opencaesar/imce-vocabularies.git
  cd imce-vocabularies
```

## Build
Equivalent to owlReason task
```
./gradlew build
```

## Run OWL Reasoner
```
./gradlew owlReason
```

## Generate Docs
You must first have Bikeshed app installed from [here](https://tabatkins.github.io/bikeshed/#install-final)
```
./gradlew generateDocs
```

## Publish to Maven Local
```
./gradlew publishToMavenLocal
```
> The version of the published artifact(s) is specified in the build.gradle script

## Publish to Maven Central
```
./gradlew publish
```
> The version of the published artifact(s) is specified in the build.gradle script
> The published artifacts go to a staging area on Maven Central from which they need to be manually released.
