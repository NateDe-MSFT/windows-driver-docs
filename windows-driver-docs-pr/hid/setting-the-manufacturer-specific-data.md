---
title: Setting the Manufacturer-Specific Data
author: windows-driver-content
description: Setting the Manufacturer-Specific Data
ms.assetid: 57787e7a-2a80-476c-8027-b7c154b2f407
keywords: ["INF files WDK joysticks , manufacturer-specific data"]
---

# Setting the Manufacturer-Specific Data


## <a href="" id="ddk-setting-the-manufacturer-specific-data-di"></a>


The manufacturer-specific section that the INF file points to contains one entry for each device that can be installed. Each entry contains the name of the device followed by the name of the install section, the device ID, and any compatible devices. If the device has been registered as Plug and Play compatible, then the Plug and Play ID (starting with an asterisk) should be used for the device ID. If the device has not been registered, then a device ID that is not Plug and Play compatible (that is, one not starting with an asterisk) should be used. When registering this type of device, avoid choosing an ID that conflicts with other device IDs ("Joystick," for example, would not be a good ID).

 

 




