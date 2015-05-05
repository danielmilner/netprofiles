# Net Profiles #
<img src='http://www.milnersolutions.com/netprofiles/images/netprofiles-main.png' align='right' />With Net Profiles, mobile computing becomes a whole lot easier. It eliminates the need to manually reconfigure your network settings when you move your desktop/laptop computer to another location. Once a profile is created, Net Profiles can configure your IP settings, proxy settings, mapped drives, default printer, wallpaper, and screen resolution with a click of a button; as well as run any number of user-defined applications upon activation of a profile.

Net Profiles was originally coded entirely in [SharpDevelop](http://www.icsharpcode.net/OpenSource/SD/)

## Features ##
  * Save your network settings as profiles.
  * Automatically activate wireless profiles when specified wireless connections are detected. (XP only)
  * Change IP Address, Subnet Mask, Default Gateway, Primary and Secondary DNS Servers, WINS Server, and DHCP settings with the click of a button.
  * Specifiy different mapped drives for each profile.
  * Change your default printer based on which profile you're currently using.
  * Automatically change your profile via program shortcuts created with Net Profiles.
  * Change the default homepage for Internet Explorer, Firefox, and Opera.
  * Proxy settings for Internet Explorer, Firefox, and Opera.
  * Run a user-defined list of programs when a profile is activated.
  * Maintain seperate desktop wallper for each profile.
  * Change screen resolutions and color quality when profiles are activated.
  * Can be easily translated into other languages using the enclosed XML language file.

## Version 2.1.8 (May 17, 2011) ##
  * Implemented ivan.hrhor's solutions for [Issue #1](http://code.google.com/p/netprofiles/issues/detail?id=1)
  * Added language Magyar (hu-hu) translated by Attila Csipak
  * Added language עברית (he) translated by Ariel Nemtzov

## Version 2.1.7 (May 22nd, 2009) ##
  * Fixed a looping problem with perpetually detecting the connected wireless network and applying the appropriate profile.

## Version 2.1.6 (May 14th, 2009) ##
  * **Net Profiles is now open source**
  * Added language Català (ca-es) translated by CRP GA
  * Added language Česky (cs-cz) translated by iXDave
  * Added language Portuguese-BR (pt-br) translated by Marcelo Gonçalves
  * Added language 繁體中文語言檔 (zh-tw) translated by mouson
  * Added language Español - Argentina (es-ar) translated by Nicolás A. Castro
  * Added language Polski (pl-pl) translated by Tomasz Minkina
  * Added language Русский (ru-ru) translated by Alexander Serashov

## Version History ##

### 2.1.5 (10/8/2007) ###
  * New language: Italian language translation comes packaged with installer.
  * New language: Dutch language translation comes packaged with installer.
  * New language: Chinese Simplified language translation comes packaged with installer.
  * Fixed bug: "Value cannot be null" error when applying a profile from a desktop shortcut.

### 2.1.4 (8/29/2007) ###
  * New language: German language translation comes packaged with installer.
  * Fixed bug: Some interface elements were not able to be translated.
  * Fixed bug: Getting display settings while using a language other than English did not work.

### 2.1.3 (8/27/2007) ###
  * Language update: Updated French language file is included with the installation.
  * Fixed bug: Crash when copying profiles under languages other than English.
  * Fixed bug: Some more interface elements were not being translated.

### 2.1.2 (8/27/2007) ###
  * New feature: Displays language name instead of language code.
  * New language: French language translation comes packaged with installer.
  * Fixed bug: Problem with interface not being completely translated when switching languages.
  * Fixed bug: Some interface elements were not able to be translated.

### 2.1.1 (8/20/2007) ###
  * Fixed bug: display issues when using non-standard XP visual styles.

### 2.1.0 (8/20/2007) ###
  * New feature: support for language files.
  * New feature: ability to ignore proxy settings for local connections.
  * New feature: ability to specify an Automatic Configuration Script Address.
  * New feature: the last activated profile is now highlighted in bold.
  * New feature: ability to copy profiles.
  * New feature: wallpaper preview in the profile settings dialog.
  * New feature: added support for more screen resolutions in the display settings.
  * New feature: Opera is now supported under internet settings.
  * Modification: the wireless tab is disabled in Windows Vista until I figure our how to obtain the connected wireless SSID in Vista.
  * Fixed bug: problem with adding more than 1 mapped drive to a profile.
  * Fixed bug: wireless auto-detection kept asking to apply wireless settings.

### 2.0.1 (2/14/2007) ###
  * "Check For Updates" now tells which new version is available.
  * Fixed bug: Gateway would not always change.
  * Fixed bug: DNS Servers would not always change.

### 2.0.0 (2/13/2007) ###
  * Completely rewritten in .NET 2.0.
  * Added proxy settings for Firefox.
  * Added homepage settings for Firefox.
  * Added ability to run any number of programs upon profile activation.
  * Added ability to change desktop wallpaper.
  * Added ability to change screen resolution and color quality.
  * Added ability to detect wireless network connection and automatically/prompt to activate profile.
  * Added tray icon with profile menu for easy access to profiles.

### 1.2 (11/4/2004) ###
  * Added proxy server settings for Internet Explorer.
  * Added the ability to change the default homepage for Internet Explorer.

### 1.1 (9/14/2004) ###
  * Bug fixes.

### 1.0 (9/13/2004) ###
  * First release.