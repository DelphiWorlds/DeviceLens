# Device Lens

Device Lens is a debugging tool that allows you to view logs on your mobile devices (presently **Android only**). This repository is currently for the documentation and for reporting issues

## Installing Device Lens

**NOTE**: The installers that used to be in this repository have been removed.

The latest version of Device Lens is [here](https://delphiworlds.com/devicelens/latest).

Older versions are available [here](https://delphiworlds.com/devicelens/older).

Just run the setup and follow the prompts!

## Change history:

v2.1.0 (Oct 19th, 2023)

* A number of significant changes "under the hood"
* Added ability to save the image in screenshot feature
* Added "Auto Start" feature - starts logcat immediately when a device is detected
* Suppress system beep when applying of filter by application name when pressing enter
* Other minor fixes

v2.0.3 (Jun 12th, 2023)

* Fixed device selection when there are multiple devices
* Fixed applying of filter by application name when pressing enter

v2.0.2 (May 24th, 2023)

* Fixed parsing of log output - was broken for some devices including WSA

v2.0.1 (Apr 10th, 2023)

* Fixed behaviour when changing filters (logcat was being started when it should not be)

v2.0.0 (Feb 21st, 2023)

* Major revamp of the user interface
* Added support for a number of themes
* Added saving of log output to file
* Fixed font sizing in the log output for high DPI

v1.3.0 (May 13th, 2021)

* Added screenshot function
* Added download APK function
* Added uninstall package function
* Fixed another issue with process parsing

v1.2.2 (July 20th, 2020)

* Fixed process parsing - should now work on Android 11
* Fixed SDK Installer button
* Fixed issue with device explorer not clearing package info

v1.2.1 (June 3rd, 2020)

* Fixed issue with filtering on Text and Tag

v1.2.0 (May 9th, 2020)

* Added SDK Installer function
* Added Configure device for TCP/IP mode function 
* Added filtering on Tag value (issue #5)
* Added memo below the grid to display the "text" portion of the selected row (issue #4)
* Fixed issue #6 - disable Explorer view function when no devices selected 

v1.1.0 (January 2nd, 2020)

* Added Device Explorer
* Added simulation of "doze" mode
* Fixed auto search/config for location of SDK, adb executable etc so that Device Lens can run on a machine without Delphi installed

v1.0.1 (October 3rd, 2019)

* Fixed parsing of process list for (at least) Symbol TC70 and Lenovo Tab 3 devices

v1.0.0 (September 30th, 2019)

* Initial release

## Help

### Device Lens Documentation

The documentation [starts here](./Docs/Index.md).

### Tutorial Videos

* [Introduction to Device Lens](https://www.youtube.com/watch?v=-J3PQiLQ6bw)
* Using Device Lens to help debug Delphi apps (Coming soon!)

### Slack channel

If you need help beyond the documentation/videos, please [join the Delphi Worlds Slack team](https://slack.delphiworlds.com), and go to the #devicelens channel. Dave Nottage can usually answer questions from around 07:00 until 19:00 Australian Central Standard Time (GMT +9:30), however others may also be on hand.




