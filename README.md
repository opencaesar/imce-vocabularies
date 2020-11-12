# IMCE Vocabularies

[![Build Status](https://travis-ci.org/opencaesar/imce-vocabularies.svg?branch=master)](https://travis-ci.org/opencaesar/imce-vocabularies)
[ ![Download](https://api.bintray.com/packages/opencaesar/ontologies/imce-vocabularies/images/download.svg) ](https://bintray.com/opencaesar/ontologies/imce-vocabularies/_latestVersion)
[![Documentation](https://img.shields.io/badge/Documentation-HTML-orange)](https://opencaesar.github.io/imce-vocabularies/) 

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
