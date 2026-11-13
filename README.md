# State of Decay 2: Ultimate Potato Config (v1.1 Beta)

The main goal of **Ultimate Potato Config** is to rescue playability and ensure extreme stability for *State of Decay 2* on entry-level hardware and low-end PCs (such as older Intel Core i3 processors, 4GB of RAM, and Intel UHD 620 integrated graphics).

---

### 🌟 Key Features

* **Extreme Performance Optimization:** Specifically designed for low-end hardware, older CPUs (such as Intel Core i3), systems with 4GB of RAM, and integrated graphics (such as Intel UHD 620).
* **Target 40 FPS & 640x480 Resolution:** Locks a stable frame rate ceiling and a lower native resolution to drastically reduce GPU bottlenecks, thermal throttling, and sudden stuttering.
* **Heavy Foliage & Dense Vegetation Removal:** Deeply strips down tall grass, shrubs, and dense foliage via Unreal Engine configuration tweaks to free up massive processing overhead.
* **Aggressive LOD & Shadow Scaling:** Lowers rendering distances and disables overly heavy post-processing effects, turning complex scenes into highly efficient rendering pipelines optimized for modest computers.
* **Plug & Play Installation:** Simple manual file placement (`.ini` replacements) with zero complex third-party tools required.

---

### 📋 Requirements & Additional Information

* **Game Version:** Compatible with the latest version of *State of Decay 2* for PC (Steam / Microsoft Store / Xbox App).
* **Prerequisites:**
  * A basic text editor (such as Notepad) if you wish to inspect or fine-tune the `.ini` parameters manually.
  * It is **strongly recommended** to make a backup copy of your original configuration files (`Engine.ini`, `GameUserSettings.ini`, `Scalability.ini`) before overwriting them, in case you ever want to revert to the default game settings.
* **Additional Notes:**
  * Because this mod lowers resolution and removes complex visual details (foliage, shadows, and post-processing) to maximize performance, visual fidelity will be reduced in exchange for stable frame rates and smooth gameplay on modest setups.

---

### ⚙️ Installation Instructions

1. **Prerequisites:**
   * Make sure you have *State of Decay 2* installed on your PC.
   * Completely close the game before starting the installation process.
2. **Download & Extract:**
   * Download the latest `.zip` archive from the **[Releases](https://github.com/techpaulo200/StateOfDecay2-Ultimate-Potato-Config/releases)** section on the right side of this page and extract it to a temporary folder on your desktop.
3. **Locate the game configuration folder:**
   * Open the Windows File Explorer and navigate to your game's configuration directory:
     `%LOCALAPPDATA%\StateOfDecay2\Saved\Config\WindowsNoEditor\`
     *(Tip: You can paste this path directly into the Windows File Explorer address bar).*
4. **Replace configuration files:**
   * Make a backup copy of your original configuration files just in case you want to revert the changes later.
   * Copy and paste the modified files (`Engine.ini`, `GameUserSettings.ini`, `Scalability.ini`) from the mod into the `WindowsNoEditor` folder, replacing the existing files when prompted.
5. **Launch the game:**
   * Boot up *State of Decay 2* and enjoy a much smoother and more stable gameplay experience on your low-end PC!

---

### 📜 Changelog

* **v1.1 Beta (Current)**
  * Official initial release of the mod focused on extreme stability for entry-level hardware (Intel Core i3, 4GB RAM, and Intel UHD 620 integrated graphics).
  * Implementation of an optimized fixed resolution (`640x480`) and a locked frame rate ceiling of `40 FPS` to curb heating spikes and VRAM-related stuttering.
  * Total and aggressive removal of foliage, grass, and brush density via Unreal Engine configuration parameters to drastically relieve CPU and GPU bottlenecks.
  * Deep adjustment of rendering distances (*LODs*) and disabling of heavy visual effects (full shadows and excessive post-processing).
  * Inclusion of copyright guidelines and anti-repost restrictions to safeguard project authorship.

---

### 🔒 Permissions & Custom License

All rights reserved by **techpaulo200**. By downloading and using **Ultimate Potato Config**, you agree to the following terms:

* **No Re-uploading or Redistribution:** You are strictly prohibited from re-uploading, mirroring, or hosting these files on any other website, file-sharing platform, Discord server, or mod repository. This mod is exclusive to this official GitHub repository.
* **No Unauthorized Modifications:** You may not edit, repackage, merge into modpacks, or release derivative versions of these configuration files without explicit written permission from the original author.
* **No Monetization:** You may not sell, paywall, or monetize links associated with this mod in any way.
* **Media & Showcase Credit:** You are welcome to feature this mod in YouTube videos, benchmarks, streams, or articles, provided that clear credit is given to **techpaulo200** along with a direct link to this original GitHub page.

---

### 🙏 Acknowledgements & Special Thanks

* **A Huge Thank You:** To all low-end gamers, community members, and open-source optimization pioneers whose dedication to tweaking Unreal Engine configuration files keeps older hardware running and gaming accessible to everyone.
* **Special Recognition:** To the *State of Decay 2* community for keeping the survival spirit alive, and to everyone testing and supporting optimization projects for modest hardware.
* **Inspiration:** Driven by the philosophy that hardware limitations should never stand in the way of a great gaming experience. Happy surviving!
