# GIS libraries for Windows

 [![Build status](https://ci.appveyor.com/api/projects/status/2q7qg7xqjdqamxhb?svg=true)](https://ci.appveyor.com/project/miurahr/vcpkg-gislibs) 
 [![Build Status](https://travis-ci.org/miurahr/vcpkg_gislibs.svg?branch=master)](https://travis-ci.org/miurahr/vcpkg_gislibs)
 [ ![Download](https://api.bintray.com/packages/osmfj/gislibs/vcpkg-gislibs/images/download.svg) ](https://bintray.com/osmfj/gislibs/vcpkg-gislibs/_latestVersion) 
 
## Overview

This project is to build GIS libraries on Windows using vcpkg and AppVeyor.
Also to build GIS libraries on Linux using vcpkg and Travis-CI.
There are several type of artifacts.

1. GDAL dependencies for GDAL CI test

2. GDAL and dependencies

3. GRASS, GDAL and dependencies

Currently it generates only (1) GDAL dependencies.

## Artifact

There are two types of Windows packages, 7zip archive and nuget package.
These files are published on bintray repository.

Also there are 7zip archive package for Linux/C++, which is released on
github release.

### 7zip arvhive export for Windows

https://bintray.com/osmfj/gislibs/vcpkg-gislibs


## License

Code licensed under the [MIT License](LICENSE.txt).
