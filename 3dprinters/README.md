# Innovatoriet 3d printing

## Setup

### PrusaSlicer
Prusa slicer is used as the primary slicing software for creating print jobs. Printing is done through [OctoPrint](#octoprint) with a custom profile to allow over network printing.
To upload a print job to OctoPrint the user must be connected to the Innovatoriet Wifi network.

To use PrusaSlicer, follow [this guide](#installing-prusa-slicer) to install and [this guide](#installing-config-bundles) to import the required settings.
After following the install and setup guides, its recomended to follow [this guide](#test-print) to get something going right away without to much effort.

### OctoPrint
OctoPrint is a web based control panel for 3d printers. It works over the local network and can control most asspects of the 3d printers. Normal members usualy never interact directly with OctoPrint but it is used to allow print jobs to be sent to the printer over network instead of using a SD card.

## Test print
Haven't printed on innovatoriet before and want to test? Follow this guide to print your first part
1. Download the 3dBenchy.stl file
2. Open Prusa Slicer
3. Go to `File > import > import (STL/3MF/...)`
4. Select the downloaded stl file
5. Click `Slice` at the bottom right corner
6. Make sure you are connected to `Innovatoriet` WIFI
7. Click `Send to printer` (its the small G symbol beside `Export G-code` at the bottom right)
8. Click `Upload and Print`

Your print is now being printed!
It takes a while before the printer starts moving as it has to heat itself first. You can see heating progres on the printers display.
When its done heating the print should begin.

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
9. Make sure **the only** printers that are selected are:
  - *Prusa MK4 (0.4mm)*
  - *Prusa MK3S & MK3S+ (0.4mm)*
11. Click Finish


## Installing config bundles
1. Download the desired config bundle from [/configs](https://github.com/Innovatoriet/Innovatoriet/tree/main/3dprinters/configs)
   - Config bundles have `.ini` as file extension.
3. Open PrusaSlicer
4. Navigate to `file > import > import config bundle`
   - IMPORTANT: Make sure to pick "import config **bundle**" and not "import config". The import will not work otherwise.
5. Choose the downloaded config bundle (usualy in the downloads folder)
6. Click open
7. If no error apeared the config should now be installed.
