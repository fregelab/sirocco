[![Build Status](https://travis-ci.org/fregelab/sirocco.svg?branch=master)](https://travis-ci.org/fregelab/sirocco)
[![Bintray](https://img.shields.io/bintray/v/fregelab/maven/sirocco-core.svg?style=flat-square)](https://bintray.com/fregelab/maven/sirocco-core)

# Sirocco

Sirocco is a Frege library to access relational databases via jdbc.
Documentation is available at https://fregelab.github.io/sirocco

Sirocco first started as some ideas based on project:
https://github.com/DellCliff/frege-dbc

## Dependencies

Binaries are available at Bintray:

    repositories {
        maven {
            url  "http://dl.bintray.com/fregelab/maven"
        }
    }

Gradle dependencies:

    compile 'com.github.fregelab:sirocco-core:0.1.2'

## Examples

The `sirocco-samples` project joins `Sirocco` and `Chinook` together
to show how a full Frege app may look like. To run the app, on the
project root folder:

    ./gradlew :sirocco-samples:run

Or to only play with the code:

    ./gradlew :sirocco-samples:fregeRepl
