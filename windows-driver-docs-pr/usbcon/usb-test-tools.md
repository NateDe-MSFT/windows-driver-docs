---
Description: Describes various tools you can use to test USB devices and drivers.
title: USB test tools
author: windows-driver-content
ms.author: windowsdriverdev
ms.date: 04/20/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
---

# USB test tools


Describes various tools you can use to test USB devices and drivers.

## In this section


<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Topic</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>[MuttUtil](muttutil.md)</p></td>
<td><p>MuttUtil performs various tasks on [MUTT devices](microsoft-usb-test-tool--mutt--devices.md).</p>
<ul>
<li>Updates the firmware of the test devices.</li>
<li>Installs drivers for MUTT devices.</li>
<li>Verifies that the devices are installed without errors.</li>
<li>Changes the operating bus speed of the device.</li>
<li>Configures the device to send a resume wake signal after a specified time period.</li>
<li>For the MUTT Pack, it sets the hub to operate at full or high speed; as a single-TT or multi-TT hub.</li>
</ul>
<p>MuttUtil is embedded in the installation section of the included test scripts to ensure that the test device is properly upgraded to latest firmware. The tool is included in the [MUTT Software Package](http://go.microsoft.com/fwlink/p/?linkid=617710).</p></td>
</tr>
<tr class="even">
<td><p>[USB client driver verifier](how-to-send-a-usb-device-to-select-suspend.md)</p></td>
<td><p>This topic describes the USB client driver verifier feature of the USB 3.0 driver stack that enables the client driver to test certain failure cases.</p></td>
</tr>
<tr class="odd">
<td><p>[USB hardware verifier (USB3HWVerifierAnalyzer.exe)](how-to-retrieve-information-about-a-usb-device.md)</p></td>
<td><p>This topic describes the USB hardware verifier tool (USB3HWVerifierAnalyzer.exe) that is used for testing and debugging specific hardware events.</p></td>
</tr>
<tr class="even">
<td><p>[USBLPM](usblpm-tool.md)</p></td>
<td><p>The USBLPM tool monitors the U0/U1/U2/U3 power states of USB 3.0 ports. It can also be used to verify that transitions between U0/U1/U2 occur correctly. In addition, the tool can enable or disable U1 and/or U2 states on all devices in the system.</p></td>
</tr>
<tr class="odd">
<td><p>[USBStress](usbstress.md)</p></td>
<td><p>USBStress is the combination of a user-mode application (usbstress.exe) and driver installation package for the kernel-mode driver, usbstress.sys.</p></td>
</tr>
<tr class="even">
<td><p>[USBTCD](usbtcd.md)</p></td>
<td><p>USBTCD is the combination of a user-mode application and kernel-mode driver. The tool performs read and write operations. It initiates control, bulk, isochronous, data transfers of various transfer lengths to and from the test device. For a SuperMUTT device, USBTCD transfers data to streams supported by a bulk endpoint. It can also send the transfer buffer as chained MDLs. In that case, you can specify the number of segments in the transfer buffer.</p></td>
</tr>
<tr class="odd">
<td><p>[USB XHCIWMI](usb-xhciwmi.md)</p></td>
<td><p>XHCIWMI is a tool for diagnostic purposes. This tool only runs on Windows 8 and gathers information when the device is attached to an xHCI port and Windows loads the Microsoft USB 3.0 driver stack.</p></td>
</tr>
</tbody>
</table>

 

## Related topics
[USB Diagnostics and Test Guide](usb-driver-testing-guide.md)  



