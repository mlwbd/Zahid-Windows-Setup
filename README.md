---
description: >-
  Follow this detailed guide to set up and customize your Windows installation
  with ease. Let's make your Windows experience smoother and more efficient! 🚀
---

# 💻Windows Setup💻

## 📋 Table of Contents

<details>

<summary>Click to Expand Table of Contents</summary>

1. [Installing Windows](broken-reference)
   * [Downloading Windows](broken-reference)
   * [Customizing Windows](broken-reference)
     * [General Customizations](broken-reference)
     * [Remove Legacy Software](broken-reference)
     * [UI Preferences](broken-reference)
     * [Power Settings](broken-reference)
     * [Network and Region Settings](broken-reference)
     * [Other Settings](broken-reference)
     * [Ghost Toolbox Utilities](broken-reference)
2. [Setting Up Software](broken-reference)
3. [Setting Up Browser Extensions](broken-reference)
4. [Setting Up Android](broken-reference)

</details>

***

## 1️⃣ Installing Windows

### 1.1 - Downloading Windows

1. **Download a Custom Windows Build**
   * Visit [Ghost Spectre](https://ghostclouds.xyz/wp/w11-24h2-pro/) for a lightweight, customizable Windows version.
   * Extract the downloaded file using the provided password.
2. **Backup Drivers**
   * Use [Iobit Driver Booster](https://www.teamos.xyz/search/1847348/?q=iobit+driver+booster\&o=date) to backup drivers.
3. **Choose the Version**
   * Opt for the **Pro Compact + Defender** version for optimal performance.
4. **Fresh Installation or Upgrade**
   * For fresh installs: Don't worry about data loss; it's stored in the `windows.old` folder (C drive).
   * For upgrades: Retain files and apps, then clean up old installations.
     * Go to **Disk Cleanup** → Select **C Drive** → **Clean Up System Files** → Delete **Old Windows Installation**.

<details>

<summary>📸 Screenshots</summary>

![Alt text](https://imgur.com/3NWJxxf.png)\
![Alt text](https://imgur.com/clGR79b.png)\
![Alt text](https://imgur.com/KmzNUJ2.png)

</details>

***

### 1.2 - Customizing Windows

#### General Customizations

* Use a **Local Account** instead of a Microsoft Account for faster login.
* Activate Windows:
  *   Run this command in PowerShell as Administrator:

      ```powershell
      irm https://get.activated.win | iex
      ```
* Restore Drivers: Use Iobit Driver Booster. Update touchpad or display drivers if needed.
  * **For Touchpad Issues**: Update **Synoptic Touchpad** via Microsoft Store.

#### Remove Legacy Software

* Remove outdated software (e.g., Paint, Media Player) via:
  * **Settings** → **Apps** → **Optional Features**.
  *   If unresolved, run this command in PowerShell as Administrator:

      ```powershell
      Disable-WindowsOptionalFeature -Online -FeatureName "WindowsMediaPlayer" -NoRestart
      ```

#### UI Preferences

* **Set Default View**: Change File Explorer view to **This PC**.
* **Turn Off Bitlocker**: Disable Bitlocker on drives to avoid encryption issues.
* **Taskbar Alignment**: Align the taskbar to the left.

#### Power Settings

* Customize **Lid & Power Button Controls** to suit your needs.

<details>

<summary>📸 Screenshots</summary>

![Alt text](https://imgur.com/9fQf7AX.png)\
![Alt text](https://imgur.com/CL5N7yH.png)\
![Alt text](https://imgur.com/B7xY3VD.png)\
![Alt text](https://imgur.com/1fO2NmH.png)

</details>

#### Network and Region Settings

* Enable **Metered Connection** for Wi-Fi to limit background data usage.
* Change **Language & Region** to **English (India)**.
* Switch **Date & Time Format** to a 12-hour clock.

<details>

<summary>📸 Screenshots</summary>

![Alt text](https://imgur.com/JXWvF9U.png)\
![Alt text](https://imgur.com/NMWyoeI.png)

</details>

#### Other Settings

* Turn off **Game Bar** and unnecessary startup programs.
* Enable and update **Virus & Threat Protection**.
* Enable **Clipboard** (press `Win + V`).

***

### 1.3 - Ghost Toolbox Utilities

1. Install essential components:
   * **Visual C++ Redistributables AIO** and **DirectX**.
2. Set up **Windows Recovery**.

<details>

<summary>📸 Screenshots</summary>

![Alt text](https://imgur.com/sNDlnfe.png)\
![Alt text](https://imgur.com/wP7gz44.png)\
![Alt text](https://imgur.com/n1i5c3G.png)\
![Alt text](https://imgur.com/LXtIlcR.png)\
![Alt text](https://imgur.com/PS8u0Kt.png)

</details>

3. Turn off Search Highlights

![Alt text](https://imgur.com/7P9xzpe.png)\
![Alt text](https://imgur.com/bW6U9KV.png)\
![Alt text](https://imgur.com/EVXdfti.png)

#### Additional Resources

* **Disk Partitioning**: Use [DiskBenchmark](https://www.diskgenius.com/free.php).
* **Fix Real-time Protection Issues**: [Watch Guide](https://www.youtube.com/watch?v=B22FMrO-vYM).
* **Reset Password or PIN**: [Watch Guide](https://www.youtube.com/watch?v=-0crAEE-6hA).
* **Identify Drivers Causing Blue Screens**: [Watch Guide](https://www.youtube.com/watch?v=Dw266cVGXic).

***

## 2️⃣ Setting Up Software

### 2.1 - Installing from Ghost Toolbox

* Install MS- Store, Calculator, Photos , Paint, Snip & Sketch , Sticky Notes, Telegram ![Alt text](https://imgur.com/7YmOo34.png)
* Install Browser
* Chrome/Mozilla/Edge (Install Webview its necessary for some microsoft features, also remove edge if you want)

<details>

<summary>📸 Screenshots</summary>

![Alt text](https://imgur.com/OIPzZd1.png)\
![Alt text](https://imgur.com/D2Lh7A8.png)\
![Alt text](https://imgur.com/Ber3MVF.png)

</details>

* Install Nilesoft Shell (Fixing Right Click Menu) & Choose Dark or Ghost Configs

<details>

<summary>📸 Screenshots</summary>

!\[Alt text]\(https://imgur.com/A2iwJnQ.png) !\[Alt text]\(https://imgur.com/r2WwynK.png) !\[Alt text]\(https://imgur.com/WZNPOq3.png)

</details>

### 2.2 - Installing from Microsoft Store

1. [Notpad](https://apps.microsoft.com/detail/9MSMLRH6LZF3?hl=en-us\&gl=IN\&ocid=pdpshare)
2. [Nanazip](https://apps.microsoft.com/detail/9N8G7TSCL18R?hl=en\&gl=IN\&ocid=pdpshare) (for unzip)
3. [Screenbox](https://apps.microsoft.com/detail/9NTSNMSVCB5L?hl=en-us\&gl=IN\&ocid=pdpshare) (media player)
4. [ShareX](https://apps.microsoft.com/detail/9NBLGGH4Z1SP?hl=en-us\&gl=IN\&ocid=pdpshare) (for screenshot & recording)
5. [Fluent Search](https://apps.microsoft.com/detail/9NK1HLWHNP8S?hl=en-us\&gl=IN\&ocid=pdpshare) (Launcher)

### 2.3 - Installing from Other Sources

1. [Adb App Control](https://adbappcontrol.com/en/#download) (removing blotware from mobile)
2. [Anydesk](https://apps.microsoft.com/detail/9N8G7TSCL18R?hl=en\&gl=IN\&ocid=pdpshare) (for remote)
3. [Bulk Crap Uninstaller](https://apps.microsoft.com/detail/9NTSNMSVCB5L?hl=en-us\&gl=IN\&ocid=pdpshare) (Uninstaller)
4. [Chrome Remote Desktop](https://remotedesktop.google.com/?pli=1) (for remote)
5. [Ezviz Studio](https://support.ezviz.com/download) (for ezviz camera control)
6. [Everything](https://www.voidtools.com/downloads/) (Search Files)
7. [Everything Toolbar](https://github.com/srwi/EverythingToolbar) (Everything Search Bar)
8. [Git](https://git-scm.com/downloads/win) (for version control)
9. [HTTP Toolit](https://httptoolkit.com/) (for intercepting requests & Response)
10. Internet Download Manager [IDM from Teamos](https://www.teamos.xyz/search/1848235/?q=internet+download+manager\&o=date) [IDM from Lrepacks](https://lrepacks.net/repaki-programm-dlya-interneta/56-internet-download-manager-repack.html) (for Downloading)
11. [Adb App Control](https://adbappcontrol.com/en/#download) (removing blotware from mobile)
12. [Iobit Uninstaller](https://www.teamos.xyz/search/1848240/?q=Iobit+uninstaller\&o=date) (Uninstaller)
13. [Office Products](https://filecr.com/windows/office-c2r-install/) (Office/PowerPoint/Excel)
14. [Obsidian](https://remotedesktop.google.com/?pli=1) (for remote)
15. [PDF Gear](https://support.ezviz.com/download) (for ezviz camera control)
16. [PoweToys](https://www.voidtools.com/downloads/) (Search Files)
17. [Python](https://github.com/srwi/EverythingToolbar) (Everything Search Bar)
18. [Quick Share](https://git-scm.com/downloads/win) (for version control)
19. [QuickLook](https://httptoolkit.com/) (for intercepting requests & Response)
20. [Stardock Fences](https://apps.microsoft.com/detail/9NBLGGH4Z1SP?hl=en-us\&gl=IN\&ocid=pdpshare) (for screenshot & recording)
21. [Sumatra PDF](https://apps.microsoft.com/detail/9NBLGGH4Z1SP?hl=en-us\&gl=IN\&ocid=pdpshare) (for screenshot & recording)
22. [Winfsp](https://apps.microsoft.com/detail/9NBLGGH4Z1SP?hl=en-us\&gl=IN\&ocid=pdpshare) (for screenshot & recording)
23. [WinSetView](https://apps.microsoft.com/detail/9NBLGGH4Z1SP?hl=en-us\&gl=IN\&ocid=pdpshare) (for screenshot & recording)
24. [Xender](https://apps.microsoft.com/detail/9NBLGGH4Z1SP?hl=en-us\&gl=IN\&ocid=pdpshare) (for screenshot & recording)
25. [Listary](https://apps.microsoft.com/detail/9NBLGGH4Z1SP?hl=en-us\&gl=IN\&ocid=pdpshare) (for screenshot & recording)
26. [AutoRuns](https://apps.microsoft.com/detail/9NBLGGH4Z1SP?hl=en-us\&gl=IN\&ocid=pdpshare) (for screenshot & recording)
27. [Winfsp](https://apps.microsoft.com/detail/9NBLGGH4Z1SP?hl=en-us\&gl=IN\&ocid=pdpshare) (for screenshot & recording)
28. [WinSetView](https://apps.microsoft.com/detail/9NBLGGH4Z1SP?hl=en-us\&gl=IN\&ocid=pdpshare) (for screenshot & recording)
29. [Xender](https://apps.microsoft.com/detail/9NBLGGH4Z1SP?hl=en-us\&gl=IN\&ocid=pdpshare) (for screenshot & recording)

***

## 3️⃣ Setting Up Browser Extensions

***

## 4️⃣ Setting Up Android

1. Configure Android for syncing with Windows.
2. Install apps for cross-platform integration.

***
