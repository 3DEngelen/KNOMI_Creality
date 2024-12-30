# Knomi Creality Logo Firmware
This repository hosts a firmware version for the knomi V2 WIth Creality logo instead of he Voron Logo.
<div align="center">
  <img src=Images/Dummy_13_Creality.png width="400" /><br/>
</div>


## KNOMI2
Online manual ：[here](https://bigtreetech.github.io/docs/KNOMI2.html#)




## Firmware source code
The firmware sourcecode can be reached by switching to the firmware branch of this repository.

## Firmware update
The buildfile of the can be found in the KNOMI2 directory and can be uploaded through the web interface of the Knomi and is called firmware.bin.

### OTA
* Download the pre compiled firmware from GitHub([KNOMI1](./KNOMI1/Firmware/knomi1_firmware.bin) and [KNOMI2](./KNOMI2/Firmware/knomi2_firmware.bin)) or build your own firmware
* Enter KNOMI's IP or hostname (default is `knomi.local`) in the browser of a device with the same LAN as knomi, and then click `Update FW`<br/>
<img src=Images/ota_1.png width="400" /><br/>
* Select the firmware file just downloaded to start updating. After the update is complete, KNOMI will automatically restart and run the new firmware.<br/>
<img src=Images/ota_2.png width="400" /><br/>

