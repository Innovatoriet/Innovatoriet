# Innovatoriet 3d printing

## Setup

### PrusaSlicer
Prusa slicer is used as the primary slicing software for creating print jobs. Printing is done through [OctoPrint](#octoprint) with a custom profile to allow over network printing.
To upload a print job to OctoPrint the user must be connected to the Innovatoriet Wifi network. 

### OctoPrint
OctoPrint is a web based control panel for 3d printers. It works over the local network and can control most asspects of the 3d printers. Normal members usualy never interact directly with OctoPrint but it is used to allow print jobs to be sent to the printer over network instead of using a SD card.

## Installing Prusa Slicer

### Windows
glhf


### Linux
glhf


### MacOS
1. Go to the prusa slicer [download page](https://www.prusa3d.com/page/prusaslicer_424/)
2. Click "Download for Mac"
3. Open the installer
4. Double click "Original Prusa Drivers"
5. Drag "PrusaSlicer" to "Applications"
6. Close and delete the installer
7. Open PrusaSlicer
8. Click on "Prusa FFF"
9. Make sure **the only** printers that are selected are Prusa MK4 (0.4mm) and Prusa MK3S & MK3S+ (0.4mm)
10. Click Finish


## Installing config bundles
1. Download the desired config from /configs
2. Open PrusaSlicer
3. Navigate to `file > import > import config bundle`
4. Choose the downloaded config bundle (usualy in the downloads folder)
5. Click open
6. If no error apeared the profiles should now be installed and can (depending on the profile) be found under ht different presets.
