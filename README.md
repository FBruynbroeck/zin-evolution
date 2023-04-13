# zin-evolution

POC for the Zin in Noord project material management

## How it works:
Load two excel files from the main web page (index.html) to get the list of missing devices by floor.

The first file (master) will contain the list of devices already installed.

The second file (floor) will contain the list of devices to be installed.

A "device" is any cell value in an Excel file that starts with the letter L followed by 3 digits. For example: `L670_KAN_OFF-123_2VL-456.HE`

A floor is represented by the first 4 characters of a device name. For example: `L670`
