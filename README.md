---
description: >-
  Follow this detailed guide to set up and customize your Windows installation
  with ease. Let's make your Windows experience smoother and more efficient! 🚀
---

# 💻Windows Setup💻

## 📋 Table of Contents

<details>

<summary>Click to Expand Table of Contents</summary>

1. [Installing Windows](#installing-windows)
   * [Downloading Windows](#downloading-windows)
   * [Customizing Windows](#customizing-windows)
     * [General Customizations](#general-customizations)
     * [Remove Legacy Software](#remove-legacy-software)
     * [UI Preferences](#ui-preferences)
     * [Power Settings](#power-settings)
     * [Network and Region Settings](#network-and-region-settings)
     * [Other Settings](#other-settings)
     * [Ghost Toolbox Utilities](#ghost-toolbox-utilities)
2. [Setting Up Software](#setting-up-software)
   * [Installing from Ghost Toolbox](#installing-from-ghost-toolbox)
   * [Installing from Microsoft Store](#installing-from-microsoft-store)
   * [Installing from Other Sources](#installing-from-other-sources)
3. [Setting Up Browser Extensions](#setting-up-browser-extensions)
4. [Setting Up Android](#setting-up-android)

</details>

***

## 1️⃣ Installing Windows

### [1.1 - Downloading Windows](#downloading-windows)

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

***

### [1.2 - Customizing Windows](#customizing-windows)

#### [General Customizations](#general-customizations)

* Use a **Local Account** instead of a Microsoft Account for faster login.
* Activate Windows:
  *   Run this command in PowerShell as Administrator:

      ```powershell
      irm https://get.activated.win | iex
      ```
* Restore Drivers: Use Iobit Driver Booster. Update touchpad or display drivers if needed.
  * **For Touchpad Issues**: Update **Synoptic Touchpad** via Microsoft Store.

#### [Remove Legacy Software](#remove-legacy-software)

* Remove outdated software (e.g., Paint, Media Player) via:
  * **Settings** → **Apps** → **Optional Features**.
  *   If unresolved, run this command in PowerShell as Administrator:

      ```powershell
      Disable-WindowsOptionalFeature -Online -FeatureName "WindowsMediaPlayer" -NoRestart
      ```

#### [UI Preferences](#ui-preferences)

* **Set Default View**: Change File Explorer view to **This PC**.
* **Turn Off Bitlocker**: Disable Bitlocker on drives to avoid encryption issues.
* **Taskbar Alignment**: Align the taskbar to the left.

#### [Power Settings](#power-settings)

* Customize **Lid & Power Button Controls** to suit your needs.

#### [Network and Region Settings](#network-and-region-settings)

* Enable **Metered Connection** for Wi-Fi to limit background data usage.
* Change **Language & Region** to **English (India)**.
* Switch **Date & Time Format** to a 12-hour clock.

#### [Other Settings](#other-settings)

* Turn off **Game Bar** and unnecessary startup programs.
* Enable and update **Virus & Threat Protection**.
* Enable **Clipboard** (press `Win + V`).

***

### [1.3 - Ghost Toolbox Utilities](#ghost-toolbox-utilities)

1. Install essential components:
   * **Visual C++ Redistributables AIO** and **DirectX**.
2. Set up **Windows Recovery**.

***

## 2️⃣ [Setting Up Software](#setting-up-software)

### [2.1 - Installing from Ghost Toolbox](#installing-from-ghost-toolbox)

* Install MS Store, Calculator, Photos, Paint, Snip & Sketch, Sticky Notes, Telegram.
* Install Browsers: Chrome, Mozilla, Edge.
* Install **Nilesoft Shell** (Fixing Right Click Menu) & Choose Dark or Ghost Configs.

***

### [2.2 - Installing from Microsoft Store](#installing-from-microsoft-store)

1. [Notepad](https://apps.microsoft.com/detail/9MSMLRH6LZF3?hl=en-us\&gl=IN\&ocid=pdpshare)
2. [Nanazip](https://apps.microsoft.com/detail/9N8G7TSCL18R?hl=en\&gl=IN\&ocid=pdpshare) (for unzip)
3. [Screenbox](https://apps.microsoft.com/detail/9NTSNMSVCB5L?hl=en-us\&gl=IN\&ocid=pdpshare) (media player)

***

### [2.3 - Installing from Other Sources](#installing-from-other-sources)

1. [Adb App Control](https://adbappcontrol.com/en/#download) (removing bloatware from mobile)
2. [Anydesk](https://apps.microsoft.com/detail/9N8G7TSCL18R?hl=en\&gl=IN\&ocid=pdpshare) (for remote access)
3. [Bulk Crap Uninstaller](https://apps.microsoft.com/detail/9NTSNMSVCB5L?hl=en-us\&gl=IN\&ocid=pdpshare) (Uninstaller)

***

## 3️⃣ [Setting Up Browser Extensions](#setting-up-browser-extensions)

1. Install **uBlock Origin** for ad-blocking.
2. Install **Dark Reader** for dark mode support.
3. Install **LastPass or Bitwarden** for password management.

***

## 4️⃣ [Setting Up Android](#setting-up-android)

1. Configure **Your Phone App** for syncing messages and notifications.
2. Install apps like **Scrcpy** for screen mirroring.
3. Use **Adb App Control** to remove bloatware from Android.

***

