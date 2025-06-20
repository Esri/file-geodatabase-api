\\# FileGeodatabaseAPI_1.5.2 (1.5.1.308)
The File Geodatabase C++ API for Windows, MacOS and Linux. The API provides basic tools that allow the creation of file geodatbases, feature classes and tables. Simple features can be created and loaded. See the README included in each of the zip/tar files for a more complete list. .NET bindings are included.

## Features

## Instructions
Download the operating system/compiler varient(s) of the API that you need and unzip it into a folder.

Linux (64-bit):
FileGDB_API-RHEL7-64gcc83.tar.gz
FileGDB_API_RHEL7_64.tar.gz

MacOS:
FileGDB_API_MACOSX15_64clang.zip
FileGDB_API_MACOSX15_64gcc8.zip

Windows:
FileGDB_API_VS2017.zip
FileGDB_API_VS2019.zip

## Requirements

#####Windows
        Windows 2008 Server Standard, Enterprise & Datacenter (64-bit) SP2
        Windows 2008 R2 Server Standard, Enterprise, and Datacenter (64-bit)
        Windows 2012 Server Standard and Datacenter (64-bit)  
        Windows 2012 R2 Server Standard and Datacenter (64-bit)  	 
        Windows 7 Ultimate, Enterprise, Professional, Home Premium (64-bit)
        Windows 8.1 Enterprise, Professional  (64-bit)
        Windows 10 Enterprise, Professional (64-bit)  

         For more information, see http://www.microsoft.com/visualstudio/11/en-us/products/compatibility
         See the same link for deployment options.
		
		Visual Studio 2012 SP4 (C++) Premium, Professional, Ultimate or Team Editions required for development.
        Visual Studio 2012 C and C++ Runtimes required for deployment.
        .NET 4.5 Framework is required for the .NET wrapper.
		
		Visual Studio 2013 SP1 (C++) Premium, Professional, Ultimate or Team Editions required for development.
        Visual Studio 2013 C and C++ Runtimes required for deployment.
        .NET 4.5.1 Framework is required for the .NET wrapper
		
		Visual Studio 2015 SP1 (C++) Premium, Professional, Ultimate or Team Editions required for development.
        Visual Studio 2015 C and C++ Runtimes required for deployment.
        .NET 4.5.1 Framework is required for the .NET wrapper.
		
		Visual Studio 2017 SP1 (C++) Premium, Professional, Ultimate or Team Editions required for development.
        Visual Studio 2017 C and C++ Runtimes required for deployment.
        .NET 4.5.1 Framework is required for the .NET wrapper.
		 
#####Linux
        Red Hat Enterprise Linux Server 5.7+
        Red Hat Enterprise Linux Server 6.x
        Red Hat Enterprise Linux Server 7.x
        SUSE Linux Enterprise Server 11 SP4
        SUSE Linux Enterprise Server 12
        Ubuntu 14.04 LTS
        Ubuntu 16.04 LTS
		
		The minimum supported versions of gcc are version 4.1.2 on Linux.
        The minimum version of clang is clang 3.7
        If you are using gcc 5.x and above you will need to use the FileGDB API version for GCC5.
		
#####MacOS
		An Intel-based Mac is required.
		
        Yosemite (10.10)
        El Capitan (10.11)
        Sierra (10.12)
		
		The minimum supported versions of gcc are version 4.2.1 on Mac OS X.
        The minimum version of clang is clang 3.7

## Resources
* [ArcGIS Blog](http://blogs.esri.com/esri/arcgis/)
* [GeoNet] (https://geonet.esri.com/community/developers/gis-developers/file-geodatabase-api)
* Esri customers can call Technical Support for assistance or to report issues.

## Issues

Find a bug or want to request a new feature?  Please let us know by submitting an issue.

##  Known Issues 
* Concurrent access from Windows and Linux clients to the same File GeoDatabase can corrupt data. This combination should be avoided.
* SQL joins are not supported.


## Licensing
Copyright 2017 Esri

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

A copy of the license is available in the repository's [License.txt](License.txt)

[](Esri Tags: FileGDB API C++)
[](Esri Language: C++)​
