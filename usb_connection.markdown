---
layout: page
title: USB Connection
permalink: /usb/
---

<a href="/files/FreelookUSBConnection.zip">Download FreelookUSBConnection Tool</a>

**Antivirus False Positive Notice**

Microsoft Defender and other antivirus software may incorrectly detect FreelookUSBConnection.exe as a malware. This is a false positive. We have submitted our file to Microsoft for analysis and they have confirmed that it is not a malware.

<a href="/assets/report/analysis_report.png">
    <img src="/assets/report/analysis_report.png" width="400">
</a>

If the file was quarantined or deleted by Microsoft Defender, you need to add an exclusion to Windows Security.
1. Go to **Start** > **Settings** > **Update & Security** > **Windows Security** > **Virus & threat protection**.
2. Under **Virus & threat protection settings**, select **Manage settings**, and then under **Exclusions**, select **Add or remove exclusions**.
3. Select **Add an exclusion**, and then select from files, folders, file types, or process. A folder exclusion will apply to all subfolders within the folder as well.

[Source: Microsoft](https://support.microsoft.com/en-us/windows/add-an-exclusion-to-windows-security-811816c0-4dfd-af4a-47e4-c301afe13b26)

If you are using any other antivirus software and would like us to submit our file to your antivirus vendor for analysis, please contact us via email at [freelookapp@gmail.com][freelookapp-email] with the name of the vendor.

---
<br />
Perform setups in **Basic Setup** before proceeding if you haven't done so already.

**Opentrack Setup**

1. Run Opentrack software on your PC.
2. Under **Input** select **UDP over network**. Click on the settings icon next it and set the Port number to **4242**.
3. Click Start to start receiving inputs.

**App Setup**

1. Run the app.
2. Click **IP Address : Port** next to the **Start** button and turn on **USB Connection**.
3. With Opentrack running, click **Start**.

**PC (Windows) Setup**

1. Download, install and run iTunes software on your PC.
2. Connect your device to PC using a USB cable.
3. If iTunes shows an alert asking if you want to allow this PC to access information on your device, click **Continue** to grant permission.
4. If iOS shows an alert asking if you trust this PC, click **Trust**.
5. Download FreelookUSBConnection tool from <a href="/usb/">https://freelookapp.github.io/usb/</a>.
6. Extract downloaded file to a folder.
7. With iTunes, Opentrack, and the app running, run **StartUSBConnection.bat**.


[freelookapp-email]: mailto:freelookapp@gmail.com
