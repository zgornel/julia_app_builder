# A small app builder for julia

Automatizes the building of Julia apps using [PackageCompiler.jl](https://github.com/JuliaLang/PackageCompiler.jl)
[![License](http://img.shields.io/badge/license-GPL-brightgreen.svg?style=flat)](LICENSE.md)


## Installation

The installation can be done by manually by cloning the repository.


## Running
`$ julia ./build.jl /PATH/TO/APP`

The script will:
 - check that all conditions necessary to build the app are fulfilled i.e. that the required directories and files exist
 - compile the app (takes quite some time)
 - place the resulting library or executable package in `PATH/TO/APP/build`

## License

This code has an GPL license and therefore it is free as beer.


## Reporting Bugs

Please [file an issue](https://github.com/zgornel/julia_app_builder/issues/new) to report a bug or request a feature.
