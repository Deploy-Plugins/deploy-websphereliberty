# History
 
## List of Versions
 
### Version 23
 
#### Build: 23.1154049 - Date: 2023.03.23 07:05
 
Updated Jettison and log4j dependencies
 
### Version 22
 
#### Build: 22.1134888 - Date: 2022.07.12 06:33
 
Minor Fix - to pick JAVA_HOME set as per agent on linux machine
 
### Version 21
 
#### Build: 21.1100824 - Date: 2021.03.04 09:49
 
Fixing CVE:CVE-2019-4233
 
### Version 21
 
#### Build: 21.1056525 - Date: 2020.05.12 00:46
 
Fixing CVE:CVE-2019-4233
 
### Version 21
 
#### Build: 21.1026759 - Date: 2019.06.26 14:04
 
Fixing CVE:CVE-2019-4233
 
### Version 19
 
#### Build: 19.978387 - Date: 2018.05.09 15:00
 
Fixes APAR PI97742 - 'Create Collective' step incorrectly encodes userPassword with linefeed added at the end
 
### Version 18
 
#### Build: 18.974811 - Date: 2018.03.09 14:56
 
Fixes APAR PI94186 - 'Install Server Archive' step expecting 'bin' directory and unzip not preserving file permissions
 
### Version 17
 
#### Build: 17.943072 - Date: 2017.11.01 14:28
 
Updated plugin documentation to describe output properties created by Start Server and Stop Server steps.  Also fixed problem where output properties were not being set correctly when starting/stopping servers via the collective controller.
RFE 100414 - Added the context sensitive help for plugin step named Install or update application via server.xml
Fixes APAR PI88752 to stream the Liberty process output to the plugin start/stop UCD output
 
### Version 16
 
#### Build: 16.930005 - Date: 2017.08.18 11:27
 
Implements RFE 104618 to merge multiple plugin-cfg.xml(s) from multiple servers and propagates it to target web servers.
 
### Version 15
 
#### Build: 15.915950 - Date: 2017.05.23 14:40
 
Fixes APAR PI82000 Start Server Plugin step incorrectly reports failure on non-English platforms
 
### Version 14
 
#### Build: 14.912008 - Date: 2017.05.08 12:38
 
Fixes APAR PI81234 Timeout occurs on "Start Application" step in WAS Liberty Plugin
 
### Version 13
 
#### Build: 13.909701 - Date: 2017.04.22 00:13
 
Added support to handle the case where the specified Liberty installation directory only contains the directory named 'wlp', not 'bin', 'lib', etc.
Added support for starting/stopping all servers in wlp.user.dir.
 
### Version 12
 
#### Build: 12.891854 - Date: 2017.02.24 09:48
 
Fixes APAR PI77192 - Error in IBM WebSphere Liberty Plugin step JoinCollective
 
### Version 11
 
#### Build: 11.869067 - Date: 2016.12.22 13:40
 
Support property file encryption.
 
### Version 10
 
#### Build: 10.848664 - Date: 2016.11.09 11:03
 
Add a step to generate Component-Resource properties from Liberty variable tags in the configuration files.
Add a step to replace the values of Liberty variables in the configuration files with the values of Component-Resource properties.
Fix problems on Windows platforms related to spaces in paths.
 
### Version 9
 
#### Build: 9.828195 - Date: 2016.09.22 11:47
 
Add support to allow specifying multiple servers for Start/Stop Server, Create/Delete Server and Join Collective steps.
Add support to allow specifying wlp.user.dir in plugin steps.
Fixed charset issue when writing server configuration files on z/OS.
 
### Version 9
 
#### Build: 9.827833 - Date: 2016.09.21 14:21
 
Add support to allow specifying multiple servers for Start/Stop Server, Create/Delete Server and Join Collective steps.
Add support to allow specifying wlp.user.dir in plugin steps.
Fixed charset issue when writing server configuration files on z/OS.
 
### Version 8
 
#### Build: 8.802646 - Date: 2016.07.07 13:33
 
Added support for new plugin steps named Register Host, Unregister Host, Update Host and Upload File To Collective Host.
Add support for joining a server to a collective via the collective controller.
Add support for starting and stopping a server via its collective controller.
 
### Version 8
 
#### Build: 8.801347 - Date: 2016.06.27 16:27
 
Added support for new plugin steps named Register Host, Unregister Host, Update Host and Upload File To Collective Host.
Add support for joining a server to a collective via the collective controller.
Add support for starting and stopping a server via its collective controller.
 
### Version 7
 
#### Build: 7.778014 - Date: 2016.04.22 11:55
 
Fixes APAR PI60739 - Start Server step does not complete if started on Windows.
 
### Version 5
 
#### Build: 5.776152 - Date: 2016.04.18 11:29
 
Fixes APAR PI59316 - Install Server Archive step not preserving file permissions when unzipping.
 
### Version 3
 
#### Build: 3.641636 - Date: 2015.02.24 13:56
 
Fixes APAR PI35342 - compatibility defect with IBM Urbancode Deploy version 6.1.0.4 and later.
 
### Version 2
 
#### Build: 2.455142 - Date: 2013.11.20 09:03
 

 
### Version 1
 
#### Build: 1.423643 - Date: 2013.08.08 17:29
 
This plugins will give the user access to steps for interacting with WebSphere Liberty Profiles for configuration and deployment. These steps will be available in the step tree in location Application Server/Java/WebSphere Liberty.
 
### Version 0
 
#### Build: 0.0 - Date: 
 

 
### Version 0
 
#### Build: 0.0 - Date: 
 

 
### Version 0
 
#### Build: 0.0 - Date: 
 

 
### Version 0
 
#### Build: 0.0 - Date: 
 

 
