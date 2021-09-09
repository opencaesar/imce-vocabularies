# IMCE Vocabularies

[![Build Status](https://app.travis-ci.com/opencaesar/imce-vocabularies.svg?branch=master)](https://app.travis-ci.com/github/opencaesar/imce-vocabularies)
[![Release](https://img.shields.io/github/v/tag/opencaesar/imce-vocabularies?label=release)](https://github.com/opencaesar/imce-vocabularies/releases/latest)
[![Documentation](https://img.shields.io/badge/Documentation-HTML-orange)](https://opencaesar.github.io/imce-vocabularies/) 
[![Gitpod](https://img.shields.io/badge/gitpod-open-blue?logo=gitpod)](https://gitpod.io/#https://github.com/opencaesar/imce-vocabularies) 

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
You must first have Bikeshed (the app itself) installed from [here](https://tabatkins.github.io/bikeshed/#install-final)
```
./gradlew generateDocs
```

## Publish to Maven Local
```
./gradlew publishToMavenLocal
```
