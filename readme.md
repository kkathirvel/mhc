# MPLAB® Harmony 3 Configurator

MPLAB Harmony 3 is an extension of the MPLAB® ecosystem for creating
embedded firmware solutions for Microchip 32-bit SAM and PIC microcontroller
and microprocessor devices.  Refer to the following links for more information.
 - [Microchip 32-bit MCUs](https://www.microchip.com/design-centers/32-bit)
 - [Microchip 32-bit MPUs](https://www.microchip.com/design-centers/32-bit-mpus)
 - [Microchip MPLAB X IDE](https://www.microchip.com/mplab/mplab-x-ide)
 - [Microchip MPLAB Harmony](https://www.microchip.com/mplab/mplab-harmony)
 - [Microchip MPLAB Harmony Pages](https://microchip-mplab-harmony.github.io/)

This repository contains the implementation of the MPLAB Harmony 3 Configurator
(MHC) tool.  The MHC is an easy to use development tool with a Graphical User
Interface (GUI) that simplifies device setup, library selection, and
configuration, and application development.  The MHC is available as a plugin
that directly integrates with the MPLAB® X IDE or as a separate Java executable
for standalone use with other development environments.

The MHC includes a downloader tool that reads an online catalog of MPLAB
Harmony 3 library packages so that the developers can select and download the
libraries in which the they are interested.  The configurator functionality
provides a convenient, but powerful, development tool for choosing library
components from downloaded packages and configuring them for the developer’s
application.  And, the built-in code generator produces the libraries and
application starter code (usually in source form), based on the options chosen.
 - [Release Notes](./release_notes.md)
 - [MPLAB Harmony 3 MHC Wiki](https://github.com/Microchip-MPLAB-Harmony/mhc/wiki)

## Contents Summary

| File/Folder  			| Description                                             	|
|-----------------------|-----------------------------------------------------------|
| doc          			| Help documentation and licenses for libraries used.      	|
| np_templates 			| New Project templates for supported toolchains.          	|
| *.jar        			| Java implementations of MHC modules.                  	|
| mhc.jar				| Main Java executable (run: java -jar mhc.jar -h)      	|
| harmony-database.jar	| internal sub module to hold all symbols					|
| databaseUI.jar		| internal sub module to show database 						|
| mhc_utils.jar			| internal sub module for harmony utility					|
| mplx_launcher.jar		| internal sub module used with MPLABX platform				|
| runmhc.bat   			| Windows cmd batch file to run standalone MHC GUI.        	|

## Open source Libraries
Content manager uses following open sources libraries:

| Library Name                         	        | License                                                                                   |
|-----------------------------------------------|-------------------------------------------------------------------------------------------|
| cmdline.jar									| Apache License 2.0 https://github.com/remkop/picocli/blob/master/LICENSE 					|
| docking-frames-common.jar						| GNU Lesser General Public License, version 2.1 http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html	|
| docking-frames-core.jar						| GNU Lesser General Public License, version 2.1 http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html|
| freemarker.jar								| Apache License Version 2.0 https://freemarker.apache.org/docs/app_license.html			|
| jython.jar									| PSF License v2 https://github.com/jythontools/jython/blob/master/LICENSE.txt				|
| simple-xml-2.7.1.jar							| The Apache Software License, Version 2.0 http://www.apache.org/licenses/LICENSE-2.0.txt 	|
