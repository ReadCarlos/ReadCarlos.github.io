# Bomb Threat
The Bomb Threat widget allows users to determine blast radius based on the type of bomb and selected location on the map.

## Sections

* [Features](#features)
* [Requirements](#requirements)
* [Instructions](#instructions)
* [Resources](#resources)
* [Issues](#issues)
* [Contributing](#contributing)
* [Licensing](#licensing)

## Features
* Select bomb type
* Ability to allow user select a location on the map

## Requirements
* Minimum requiremnet is ArcGIS WebApp Builder v.1.0. Widget has been updated to v.2.0. 

## Instructions
In order to develop and test widgets you need to deploy the BombThreat directory to the stemapp/widgets directory in your WebApp Builder installation. The widget relies on Geoprocessing and Map services, and SD files for those services can be found in the EmergencyOperations.zip file in the [services](https://github.com/Esri/solutions-webappbuilder-widgets/tree/master/BombThreat/services) folder. The zip file contains ERG.sd which is the Geoprocessing service along with the EmergencyOperation.sd which is the accompanying map service. Please update the BombThreat config.json file once these SD files are published in ArcGIS Server.

## Issues
* Find a bug or want to request a new feature?  Please let us know by submitting an issue.

## Contributing
Esri welcomes contributions from anyone and everyone. Please see our [guidelines for contributing](https://github.com/esri/contributing).

If you are using [JS Hint](http://http://www.jshint.com/) there is a .jshintrc file included in the root folder which enforces this style.
We allow for 120 characters per line instead of the highly restrictive 80.

## Licensing
Copyright 2013 Esri

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

A copy of the license is available in the repository's
[license.txt](license.txt) file.

[](Esri Tags: ArcGISSolutions ArcGIS Defense and Intelligence Military Environment Planning Analysis Emergency Management Local-Government Local Government State-Government State Government Utilities)
[](Esri Language: Javascript)
