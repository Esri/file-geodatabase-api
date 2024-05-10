\\# FileGeodatabaseAPI_1.5.3
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
        Windows 10 version 1703 or higher: Home, Professional, Education, and Enterprise (LTSC and S are not supported) (64-bit)
        Windows 11 version 21H2 or higher: Home, Pro, Pro Education, Pro for Workstations, Enterprise, and Education (64-bit)		
        Windows Server 2016: Standard and Datacenter (64-bit)
		Windows Server 2019: Standard and Datacenter (64-bit)
		
        For more information, see http://www.microsoft.com/visualstudio/11/en-us/products/compatibility
        See the same link for deployment options.
		
        Visual Studio 2019 (C++) Premium, Professional, Ultimate or Team Editions required for development.
        Visual Studio 2019 C and C++ Runtimes required for deployment.
        .NET 4.8 Framework is required for the .NET wrapper.
		
        Visual Studio 2022 (C++) Premium, Professional, Ultimate or Team Editions required for development.
        Visual Studio 2022 C and C++ Runtimes required for deployment.
        
		.NET 4.8 Framework is required for the .NET wrapper.
		 
#####Linux
        Red Hat Enterprise Linux Server 7.x
        RedHat 8 gcc 10.4
        SUSE Linux Enterprise Server 12
        Ubuntu 18.04 LTS
	
        * The minimum supported versions of gcc are version 4.8.5 and 8.3.0 on Linux.
		
#####MacOS
        MacOS 13 Ventura x64 Intel chip
        MacOS 13 Ventura M1/M2 Apple chip.
		
        * The minimum supported versions of gcc on Mac OS X is 8.3.0
        * The minimum supported versions of clang on Mac OS X is 12.0.0
		* If you are using gcc 8.x and above you will need to use the FileGDB API version for GCC8.

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
Copyright 2022 Esri

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
