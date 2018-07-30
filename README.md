# Firmware
This repository contains MicroDAQ firmware

##How to check your MicroDAQ firmware version?

You can use MicroDAQ web interface and check Infor or Logs page to see which is the current MicroDAQ firmware version. 
If you are using Scilab and MicroDAQ toolbox for Scilab you can use command mdaqHWInfo which returns 
firmware version on the device and the latest available version.

##How to upgrade MicroDAQ firmware?

Go to http://www.microdaq.org/download.html and download latest MicroDAQ firmware. Connect your MicroDAQ device with 
USB cable and wait a few seconds, after that time MicroDAQ should be discovered as a mass storage device. Open newly discovered disk and copy the opk file from firmware archive. 
Enter MicroDAQ IP address in the web browser address e.g 10.10.1.1 or address you set for MicroDAQ device, select Upgrade
and confirm. 
After few seconds upgrade should be completed and after restarting MicroDAQ device you can check MicroDAQ firmware version in the Info page. 

