# GIS libraries for Windows

 [![Build status](https://ci.appveyor.com/api/projects/status/2q7qg7xqjdqamxhb?svg=true)](https://ci.appveyor.com/project/miurahr/vcpkg-gislibs) 
 [![Build Status](https://travis-ci.org/miurahr/vcpkg_gislibs.svg?branch=master)](https://travis-ci.org/miurahr/vcpkg_gislibs)
 [ ![Download](https://api.bintray.com/packages/osmfj/gislibs/vcpkg-gislibs/images/download.svg) ](https://bintray.com/osmfj/gislibs/vcpkg-gislibs/_latestVersion) 
 
## Overview

This project is to build GIS libraries on Windows using vcpkg and AppVeyor.
Also to build GIS libraries on Linux using vcpkg and Travis-CI.

## Artifact

There are two types of Windows packages, 7zip archive and nuget package.
These files are published on bintray repository.

Also there are 7zip archive package for Linux/C++, which is released on
github release.

### Provided libraries

Following libraries are included in an archive file.

 - bzip2
 - liblzma
 - zlib
 - charls
 - curl
 - libxml2
 - expat
 - libiconv
 - libpng
 - giflib
 - glib
 - tiff
 - hdf5
 - libgeotiff
 - libgta
 - libjpeg-turbo
 - libwebp
 - fontconfig
 - freetype
 - proj4
 - sqlite3
 - pcre
 - geos
 - boost-system
 - boost-regex
 - boost-thread
 - freexl(*)
 - libspatialite(*)
 - openjpeg(*)

(*) Only windows binary are provided.

### 7zip archive export for Windows

https://bintray.com/osmfj/gislibs/vcpkg-gislibs

### 7zip archive export for Linux

https://github.com/miurahr/vcpkg_gislibs/releases

## License

Code licensed under the [MIT License](LICENSE.txt).
