# Oracle APEX Item Plugin - ClockPicker

[![APEX Community](https://cdn.rawgit.com/Dani3lSun/apex-github-badges/78c5adbe/badges/apex-community-badge.svg)](https://github.com/Dani3lSun/apex-github-badges) [![APEX Plugin](https://cdn.rawgit.com/Dani3lSun/apex-github-badges/b7e95341/badges/apex-plugin-badge.svg)](https://github.com/Dani3lSun/apex-github-badges)
[![APEX Built with Love](https://cdn.rawgit.com/Dani3lSun/apex-github-badges/7919f913/badges/apex-love-badge.svg)](https://github.com/Dani3lSun/apex-github-badges)

ClockPicker is a item type plugin that gives you a nice clock-style overlay above of an input field.
It is based on JS Framework clockpicker (https://github.com/weareoutman/clockpicker).

## Changelog
#### 1.7.0 - Bug fixes for APEX 5.1 (Button rendering was buggy) / Code Cleanup using separate JavaScript file / fixed issue #8

#### 1.6.1 - fixed clockpicker button style

#### 1.6 - added possibility to show a clock button on right side

#### 1.5 - updated bootstrap to 3.3.6 and fixed css errors like issue #5

#### 1.4 - added possibility to suppress soft keyboard fade outs on mobile devices

#### 1.3 - added source attribute to plugin (see issue #2)

#### 1.2 - fixes for problems with UT in Apex 5 (see issue #1)

#### 1.1 - added 12h mode (AM/PM Switch)

#### 1.0 - Initial Release

## Install
- Import plugin file "item_type_plugin_de_danielh_clockpicker.sql" from source directory into your application
- (Optional) Deploy the CSS/JS files from "server" directory on your webserver and change the "File Prefix" to webservers folder.

## Plugin Settings
The plugin settings are highly customizable and you can change:
- Placement (Top/Bottom)
- Alignment (Left/Right)
- Autoclose (True/False)
- 12h Mode AM/PM (True/False)
- Text of "Done" Button
- Show clock button (Yes/No)
- Suppress Mobile Keyboards (Yes/No)


## Demo Application
https://apex.oracle.com/pls/apex/f?p=APEXPLUGIN

## Preview
![](https://github.com/Dani3lSun/apex-plugin-clockpicker/blob/master/preview.png)
---
