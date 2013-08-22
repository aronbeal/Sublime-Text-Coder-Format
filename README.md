#Coder Format
This Sublime Text plugin is responsible for applying Drupal coder formatting to eligible files.  It does so leveraging the [Coder](https://drupal.org/project/coder) module for Drupal, part of which is bundled with this plugin. (Current included version is coder_format.inc 7.x-2.0).  This plugin requires that php be installed on your system.

## Installation
The recommended install is via the Package Control:
- Press ctrl+shift+p (Windows, Linux) or cmd+shift+p (OS X), start typing “Package” to access Package Manager commands
- When the list of packages is presented, search for "Coder Format", press enter to install

##Usage
Only key binding so far is for OSX, which is set to ctrl+c to invoke coder formatting.  Also available under Tools->Coder Format->Coder Format, or as a quickwindow completion of "Coder Format".  Command is set to work only for .php, .install, and .module file suffixes; this can be changed under the preferences for the module (Preferences->Package Settings->Coder Format on OSX)

