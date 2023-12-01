
# ESP32 S3 , LilyGo T-display drive for WIN7, Win8.1

This repository includes Information (INF) files containing Vendor ID (VID), Product ID (PID), and Interface IDs (MIs) for two different USB stacks related to ESP32 microcontrollers such as LilyGo T-display.


## Installation

Clone or download the repository
Navigate to Device Manager:
```bash
  Navigate to Device Manager
  Connect ESP32 Device via USB
  Right-click on the device 
  select "Update Driver Software."
  Choose Manual Installation
```
Choose "Browse my computer for driver software" and then "Let me pick from a list of device drivers on my computer."
Click "Have Disk" and browse to the location where you downloaded the repository
Choose the appropriate INF file based on the USB stack you want to install:
 ```bash
    if ESP32-S3 Serial/JTAG: Select esp32-vcp-jtag.inf
    if ESP32-IDF TinyUSB: Select esp32-tinyusb.inf
```
## Documentation


[Documentation](https://linktodocumentation)


## Appendix

if there is an issue of installation, change the  parameter in Windows 7, 8.1 and install a USB driver without checking for a digital signature. 

### Here's a guide:

You can try the steps below on how to Disable driver signing:

Press Win+R and type gpedit.msc.
Click on User Configuration on the left panel.
Double-click on Administrative Templates.
Double-click on System and select Driver Installation.
Select Enabled, from the drop-down items, select Ignore.
Click OK to apply the changes.
Restart your device.

## Demo

Insert gif or link to demo


## Tech Stack

**Hardware:** ESP32 S3, LilyGo T-Display

**System:** Windows 7, Windows 8.1


## Support

For support, email narimanana2020@gmail.com or Text/call me on 00 261 34 68 325 40.

