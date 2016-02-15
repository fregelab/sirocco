[![Build Status](https://travis-ci.org/januslynd/sirocco.svg?branch=master)](https://travis-ci.org/januslynd/sirocco)
[![Bintray](https://img.shields.io/bintray/v/januslynd/maven/sirocco-core.svg?style=flat-square)](https://bintray.com/januslynd/maven/sirocco-core)

# Sirocco

Sirocco is a Frege library to access relational databases via jdbc.
Documentation is available at https://januslynd.github.io/sirocco

Sirocco first started as some ideas based on project:
https://github.com/DellCliff/frege-dbc

## Dependencies

Binaries are available at Bintray:

    repositories {
        maven {
            url  "http://dl.bintray.com/januslynd/maven"
        }
    }

Gradle dependencies:

    compile 'com.github.januslynd:sirocco-core:0.1.1'

## Examples

The `sirocco-samples` project joins `Sirocco` and `Chinook` together
to show how a full Frege app may look like. To run the app, on the
project root folder:

    ./gradlew :sirocco-samples:run

Or to only play with the code:

    ./gradlew :sirocco-samples:fregeRepl
