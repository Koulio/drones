## Development Enviornment

This describes the development platform, packaged within a (large)
VMware Fusion 8 .vmwarevm bundle (WIN-HIJA4A33DRG) with 3.37 GB RAM running within a 2.49 GHz Mac OSX Yosemite.

NOTE: Fusion 8 places emphasis on graphics-intensive virtualization
(supporting DirectX 10 and OpenGL 3.3). See http://www.networkworld.com/article/3023246/virtualization/review-run-windows-10-on-your-mac-using-vmware-s-fusion-8.html

## Windows 7 Base Utilities
These are installed:

* Windows 7 Ultimate SP1
* Chocolatey
* Java 7.0.79.1 using cinst jdk7 from https://chocolatey.org/packages/jdk7
  (not jdk-7u79-windows-x64.exe from http://www.oracle.com/technetwork/java/javase/downloads/jdk7-downloads-1880260.html)
* 7z938-x64.msi
* Git-1.9.5-preview20141217.exe

* android-studio-bundle-141.2456560-windows.exe from http://developer.android.com/sdk/installing/index.html?pkg=studio
* SourceTreeSetup_1.6.20.exe

<hr />

<a name="MobileSDK">
## Mobile SDK</a>
DJI's Mobile SDK at home page https://developer.dji.com/mobile-sdk/
consists of:

* Firmware for each DJI model (Phantom 3, Inspire 1, OSMO, 
* DJI PC Simulator Installer & User Manual
* WIN Driver Installer
* iOS SDK and SDK Sample and Release Notes
* Android SDK and SDK Sample and Release Notes for version 3.0.1 on Feb 4, 2016, update from 2.4)
 
http://developer.dji.com/mobile-sdk/documentation/
provides docs on classes, protocols, constants generated from code at
https://github.com/dji-sdk/Mobile-SDK-Android/tree/master/Sample%20Code

But more useful is https://developer.dji.com/en/get-started/mobile-sdk/Mobile-SDK-Features/

Contributors include https://github.com/JonasVautherin
who also contributed to https://github.com/3drobotics/solodevguide
and http://code.opencv.org/projects/opencv/wiki
doing http://code.opencv.org/projects/opencv/wiki/FaceDetection
Gary Bradski, President and CEO, OpenCV Foundation

### DJI PC Simulator Installer
Download from DJI's Mobile SDK at home page https://developer.dji.com/mobile-sdk/

DJISimulator-Installer.exe
requires DJI_WIN_Driver_Installer.exe installed into C:\Program Files (x86)\DJI Product\DJI driver2.02
and does not run on Windows 10 (only to Windows 8.1).

DJISimulator-Installer.exe within DJI_PC_Simulator_Installer_And_User_Manual_V1.0_en
into C:\Program Files (x86)\DJISimulator.

* https://developer.dji.com/en/get-started/mobile-sdk/Mobile-SDK-API-Introduction/
  contains color pictures of what is in DJI PC Simulator User Manual.pdf downloaded,
  except call-outs of flight data is transmitted to the PC through the UDP port 5566.
  The PC can interpret this data to create a virtual 3D environment for analysis.

<strong>WARNING: Use of Simulator requires the drone be connected to Windows via USB cable</strong>

