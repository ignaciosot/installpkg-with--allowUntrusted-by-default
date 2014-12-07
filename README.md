# InstallPKG #

InstallPKG is a wrapper to the 'installer' tool on Mac OS X systems. The functionality is focused on allowing you to quickly and easily install multiple packages to the current boot drive.  InstallPKG is released under the GNU GPL licence.

Download the latest version (a compiled package installer) via the following URL : 
http://www.lucid.systems/download/installpkg

Use this GitHub project to build the OS X package installer for InstallPKG or download the .dig file which is also available from github. Pull requests to add useful features or bug fixes are also welcome.

Support for URL install package source files is provided by wget. If you do not have wget installed on your system and you would rather not install the developer tools then download wget for OS X as a package from : http://rudix.org/packages/wget.html

Basic usage example to install all .pkg files found within a specific directory : installpkg /path/to/directory/of/packages/*

Full usage information and examples are availibe by typing 'man installpkg' once installed.

Comments and suggestions regarding the InstallPKG project are very welcome.
