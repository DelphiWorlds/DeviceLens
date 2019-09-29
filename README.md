# Device Lens
Device Lens is a debugging tool that allows you to view logs on your mobile devices (presently **Android only**). This repository is currently just for basic help, the installers and for reporting issues

##Change history:

v1.0.0 (September 30th, 2019)

* Initial release

## Basic Help

### Android

Device Lens lists the connected devices in the list on the top left. Selecting a device will show what processes are running on the device. Double clicking a process name will start the log display and filter on that process.

Clicking the **Play** button in the toolbar will start displaying the logs coming from the device. The Play button will turn into a **Stop** button once the log display starts.

You can filter on text that appears in the log display by typing in the Filter On Text edit. This filter supports basic wildcards by using an asterisk at the beginning or end of the filter.

You can manually enter a process name (package name) in the Filter On Package Name edit. Press enter once you have finished typing to enable the filter

You can use the Filter By Log Level checkboxes to filter messages based on their log level. The Toggle button changes all the checkboxes to the opposite of the most prevalent state of the checkboxes.

The Auto Scroll checkbox controls whether the log display scrolls automatically to the last entry




