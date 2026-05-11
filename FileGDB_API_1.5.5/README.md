
# FileGeodatabase API_1.5.5
The File Geodatabase C++ API for Windows.
MacOS M1/M2 coming soon.

The API provides basic tools that allow the creation of file geodatbases, feature classes and tables. Simple features can be created and loaded. See the README included in each of the zip/tar files for a more complete list. .NET bindings are included.

## What's New
Pick up security fixes for components used by the API.

## Fixed
Expat updated from 2.6.4 to 2.7.3

Libxslt updated from 1.1.43 to 1.1.45

Libxml2 updated from 2.13.6 to 2.15.1

## Instructions
Download the operating system/compiler varient(s) of the API that you need and unzip it into a folder.

### Linux (64-bit):
    Supported via Rocky 9, same tar file.
	RedHat 9
	Ubuntu 20.04
	Ubuntu 24.04

### MacOS:
    MacOS 13 Ventura x64 Intel chip
    MacOS 13 Ventura M1/M2 Apple chip.
	
### Windows:
	FileGDB_API_VS2022.zip - Built with Microsoft Visual Studio 2022
	
## Requirements
### Windows
    The supported platforms (for development) are:

    Windows 11 minimum supported OS version or higher: Home, Pro, Pro Education, Pro for Workstations, Enterprise, and Education (64-bit)  
    Windows server 2022 

    For more information, see https://learn.microsoft.com/en-us/visualstudio/releases/2022/system-requirements#visual-studio-2022-system-requirements
    See the same link for deployment options.
	
    Visual Studio 2022 (C++) Premium, Professional, Ultimate or Team Editions required for development.
    Visual Studio 2022 C and C++ Runtimes required for deployment.
    .NET 4.8 Framework is required for the .NET wrapper.

## Resources
ArcGIS Blog
[GeoNet] (https://geonet.esri.com/community/developers/gis-developers/file-geodatabase-api)
Esri customers can call Technical Support for assistance or to report issues.
Issues
Find a bug or want to request a new feature? Please let us know by submitting an issue.

## Known Issues
Concurrent access from Windows and Linux clients to the same File GeoDatabase can corrupt data. This combination should be avoided.
SQL joins are not supported.
## Licensing
Copyright 2026 Esri

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

A copy of the license is available in the repository's License.txt

[](Esri Tags: FileGDB API C++) [](Esri Language: C++)​
