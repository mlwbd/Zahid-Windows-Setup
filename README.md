---
description: >-
  Follow this detailed guide to set up and customize your Windows installation
  with ease. Let's make your Windows experience smoother and more efficient! 🚀
---

# 💻Windows Setup💻

## 📋 Table of Contents

<details>

<summary>Click to Expand Table of Contents</summary>

1. [Installing Windows](./#1-installing-windows)
   * [Downloading Windows](./#id-11-downloading-windows)
   * [Customizing Windows](./#id-12-customizing-windows)
   * [Ghost Toolbox Utilities](./#id-13-ghost-toolbox-utilities)
2. [Setting Up Software](./#id-2-setting-up-software)

* &#x20;[Installing from Ghost Toolbox](./#id-2.1-installing-from-ghost-toolbox)
* [Installing from Microsoft Store](./#id-2.2-installing-from-microsoft-store)
* [Installing from Other Sources](./#id-2.3-installing-from-other-sources)
* [Customizing Software Settings](./#id-2.4-customizing-software-settings)

3. [Setting Up Browser](./#id-3-setting-up-browser-extensions)
4. [Setting Up Android](./#4-setting-up-android)

</details>

***

## 1️⃣ Installing Windows <a href="#id-1-installing-windows" id="id-1-installing-windows"></a>

### <mark style="color:green;">1.1 - Downloading Windows</mark> <a href="#id-11-downloading-windows" id="id-11-downloading-windows"></a>

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

### <mark style="color:green;">1.2 - Customizing Windows</mark> <a href="#id-12-customizing-windows" id="id-12-customizing-windows"></a>

#### General Customizations <a href="#id-12-general-customizations" id="id-12-general-customizations"></a>

* Use a **Local Account** instead of a Microsoft Account for faster login.
* Activate Windows:
  *   Run this command in PowerShell as Administrator:

      ```powershell
      irm https://get.activated.win | iex
      ```
* Restore Drivers: Use Iobit Driver Booster. Update touchpad or display drivers if needed.
  * **For Touchpad Issues**: Update **Synoptic Touchpad** via Microsoft Store.

#### Remove Legacy Software <a href="#id-12-remove-legacy-software" id="id-12-remove-legacy-software"></a>

* Remove outdated software (e.g., Paint, Media Player) via:
  * **Settings** → **Apps** → **Optional Features**.
  *   If unresolved, run this command in PowerShell as Administrator:

      ```powershell
      Disable-WindowsOptionalFeature -Online -FeatureName "WindowsMediaPlayer" -NoRestart
      ```

#### UI Preferences <a href="#id-12-ui-preferences" id="id-12-ui-preferences"></a>

* **Set Default View**: Change File Explorer view to **This PC**.
* **Turn Off Bitlocker**: Disable Bitlocker on drives to avoid encryption issues.
* **Taskbar Alignment**: Align the taskbar to the left.

#### Power Settings <a href="#id-12-power-settings" id="id-12-power-settings"></a>

* Customize **Lid & Power Button Controls** to suit your needs.

<details>

<summary>📸 Screenshots</summary>

![Alt text](https://imgur.com/9fQf7AX.png)\
![Alt text](https://imgur.com/CL5N7yH.png)\
![Alt text](https://imgur.com/B7xY3VD.png)\
![Alt text](https://imgur.com/1fO2NmH.png)

</details>

#### Network and Region Settings <a href="#id-12-network-and-region-settings" id="id-12-network-and-region-settings"></a>

* Enable **Metered Connection** for Wi-Fi to limit background data usage.
* Change **Language & Region** to **English (India)**.
* Switch **Date & Time Format** to a 12-hour clock.

<details>

<summary>📸 Screenshots</summary>

![Alt text](https://imgur.com/JXWvF9U.png)\
![Alt text](https://imgur.com/NMWyoeI.png)

</details>

#### Other Settings <a href="#id-12-other-settings" id="id-12-other-settings"></a>

* Turn off **Game Bar** and unnecessary startup programs.
* Enable and update **Virus & Threat Protection**.
* Enable **Clipboard** (press `Win + V`).

***

### <mark style="color:green;">1.3 - Ghost Toolbox Utilities</mark> <a href="#id-13-ghost-toolbox-utilities" id="id-13-ghost-toolbox-utilities"></a>

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

## 2️⃣ Setting Up Software <a href="#id-2-setting-up-software" id="id-2-setting-up-software"></a>

### <mark style="color:green;">2.1 - Installing from Ghost Toolbox</mark>

* Install MS- Store, Calculator, Photos, Paint, Snip & Sketch, Sticky Notes, Telegram\
  ![Alt text](https://imgur.com/7YmOo34.png)
* Install Browser
* Chrome/Mozilla/Edge (Install Webview its necessary for some Microsoft features, also remove Edge if you want)

<details>

<summary>📸 Screenshots</summary>

![Alt text](https://imgur.com/OIPzZd1.png)\
![Alt text](https://imgur.com/D2Lh7A8.png)\
![Alt text](https://imgur.com/Ber3MVF.png)

</details>

* Install Nilesoft Shell (Fixing Right Click Menu) & Choose Dark or Ghost Configs

<details>

<summary>📸 Screenshots</summary>

![Alt text](https://imgur.com/A2iwJnQ.png)\
![Alt text](https://imgur.com/r2WwynK.png)\
![Alt text](https://imgur.com/WZNPOq3.png)

</details>

### <mark style="color:green;">2.2 - Installing from Microsoft Store</mark>

1. [Notepad](https://apps.microsoft.com/detail/9MSMLRH6LZF3?hl=en-us\&gl=IN\&ocid=pdpshare)
2. [Nanazip](https://apps.microsoft.com/detail/9N8G7TSCL18R?hl=en\&gl=IN\&ocid=pdpshare) (for unzip)
3. [Microsoft TODO ](https://apps.microsoft.com/detail/9nblggh5r558?hl=en-US\&gl=US)(todo app)
4. [PC Manager](https://apps.microsoft.com/detail/9pm860492szd?hl=en-US\&gl=US) (windows utility)
5. [ShareX](https://apps.microsoft.com/detail/9NBLGGH4Z1SP?hl=en-us\&gl=IN\&ocid=pdpshare) (for screenshot & recording)
6. [Fluent Search](https://apps.microsoft.com/detail/9NK1HLWHNP8S?hl=en-us\&gl=IN\&ocid=pdpshare) (Launcher)

### <mark style="color:green;">2.3 - Installing from Other Sources</mark>

1. [Adb App Control](https://adbappcontrol.com/en/#download) (removing bloatware from mobile)&#x20;
2. [Anydesk](https://anydesk.com/) (for remote access)
3. [Bibata Cursor](https://github.com/ful1e5/Bibata_Cursor) (Custom Windows Cursor)
4. [Bulk Crap Uninstaller](https://www.bcuninstaller.com/) (Uninstaller)
5. [Chrome Remote Desktop](https://remotedesktop.google.com/) (for remote access)
6. [Ezviz Studio](https://support.ezviz.com/download) (for camera control)
7. [Everything](https://www.voidtools.com/) (Search Files)
8. [Everything Toolbar](https://github.com/srwi/EverythingToolbar) (Search Bar)
9. [Git](https://git-scm.com/) (version control)
10. [HTTP Toolkit](https://httptoolkit.com/) (network debugging)
11. [IDM from TeamOS](https://www.teamos.xyz/search/1848235/?q=internet+download+manager\&o=date) / [IDM from Lrepacks ](https://lrepacks.net/repaki-programm-dlya-interneta/56-internet-download-manager-repack.html)(Download Manager)
12. [IObit Uninstaller](https://www.teamos.xyz/search/1848240/?q=Iobit+uninstaller\&o=date) (Uninstaller)
13. [Microsoft Office](https://filecr.com/windows/office-c2r-install/) (Productivity Suite)
14. [Obsidian](https://obsidian.md/) (Note-taking)
15. [PDF Gear](https://pdfgear.com/) (PDF Reader)
16. [PotPlayer ](https://potplayer.daum.net/)(Media Player for m3u8)
17. [PowerToys](https://learn.microsoft.com/en-us/windows/powertoys/) (System Utilities)
18. [Python](https://www.python.org/) (Programming Language)
19. [Qbittorent ](https://www.qbittorrent.org/download)(Torrent Download)
20. [QuickShare](https://www.android.com/intl/en_in/better-together/quick-share-app/) (Transfer between Phone & PC)
21. [QuickLook](https://pooi.moe/QuickLook/) (File Preview)
22. [Stardock Fences](https://www.teamos.xyz/search/1869120/?q=stardock+fences\&o=date) (Desktop Organization)
23. [Sumatra PDF](https://www.sumatrapdfreader.org/) (PDF Reader)
24. [UniGetUI ](https://github.com/marticliment/UniGetUI)(for Updating Apps)
25. [Winfsp](https://winfsp.dev/) (File System Proxy)
26. [WinSetView](https://github.com/LesFerch/WinSetView) (File Explorer Settings)

### <mark style="color:green;">2.4 - Customizing Software Settings</mark>

> _Most software settings are user-specific and straightforward to configure. Detailed setup instructions can typically be found on the respective software's official website._

***

## 3️⃣ Setting Up Browser Extensions <a href="#id-3-setting-up-browser-extensions" id="id-3-setting-up-browser-extensions"></a>

_(Add your browser extension setup content here)_

***

## 4️⃣ Setting Up Android <a href="#id-4-setting-up-android" id="id-4-setting-up-android"></a>

1. Configure Android for syncing with Windows
2. Install apps for cross-platform integration

***
