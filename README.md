# JPL Vocabularies

[![Build Status](https://travis-ci.org/opencaesar/jpl-vocabularies.svg?branch=master)](https://travis-ci.org/opencaesar/jpl-vocabularies)
[ ![Download](https://api.bintray.com/packages/opencaesar/ontologies/jpl-vocabularies/images/download.svg) ](https://bintray.com/opencaesar/ontologies/jpl-vocabularies/_latestVersion)

This is a set of JPL vocabularies expressed in [OML](https://github.com/opencaesar/oml)

## Clone
```
  git clone https://github.com/opencaesar/jpl-vocabularies.git
  cd jpl-vocabularies
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
