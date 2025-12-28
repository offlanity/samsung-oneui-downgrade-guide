> ⚠️ **Work in Progress:** This guide is still under development. Proceed carefully and at your own risk.  
> This guide is based on the work of **u/fit_freak9** — see the original [Reddit post](https://www.reddit.com/r/GalaxyS23Ultra/comments/1l1hsh0/i_successfully_downgraded_from_one_ui_7_android/#lightbox) for reference.




# ⚠️ Important: Read the Full Documentation⚠️ 

### **This process will erase all data and may brick your device if done incorrectly. Proceed at your own risk.**

# ⚠️Disclaimer⚠️ 
This guide is shared **for educational purposes only**. It is **not official documentation**, and I am **not affiliated with Samsung or Google**.

  

By following this guide, you agree that:

  

- You are proceeding **at your own risk**

- You are **fully responsible** for anything that happens to your device

- I provide this guide **“as is”**, with **no guarantees or warranties**

- I am **not responsible** for any damage, data loss, device failure, or warranty issues

- Any problems caused by incorrect steps, misuse, or unexpected behavior are **not my responsibility**

  

Flashing or downgrading firmware can cause data loss or permanent damage if done incorrectly.

If you do not understand the risks, **do not continue**.





# 📘Guide 

In theory, any Samsung device can be downgraded as long as a compatible firmware exists and the **bootloader** can be safely **unlocked**. However, success may vary depending on region, carrier, and current OS version.

**Tested Devices:**
- Samsung Galaxy S23 Ultra (One UI 8, December Patch)
- A35 (One UI 8, December Patch)


**Notes / Limitations:**
- Devices must have **official firmware available** for the target version.  
- Carrier-locked devices may fail or require additional steps.  
- Downgrading from certain security patches may trigger errors or prevent flashing.  
- Always verify your **model number** (e.g., SM-S918B) and **region code** before downloading firmware.  


## 1. Back Up Your Data First (Important) 
**This process **will wipe all data** on your device, including internal storage, apps, and settings.**


I recommend using this tools to backup your data.
 - Samsung smart-switch (Note: Users have reported battery drain when used to restore data)
 - Google Backup
 - External drive (via computer)

>See the [Backup Guide](backup.md) for detailed instructions.

## 2. Before You Start

Ensure all requirements below are met **before** continuing.

- Hardware & System
  - **Windows PC**
  - **USB-C cable** (preferably the original Samsung cable)  
  Using damaged or low-quality third-party cables may cause connection failures or slow transfer speeds.

- Device Preparation
  - **USB Debugging enabled**
  - **All accounts removed** (especially Google and Samsung)  
  >Failure to do this may lead to **failure** 
  See: **[Remove Accounts](#3-remove-accounts)** for more

- Required Software & Files
  - **Samsung USB Drivers for Windows**  
  https://developer.samsung.com/android-usb-driver
  - **Odin 3.14**  (Make sure same version)
  https://www.odinflash.com/download
  - **ADB Platform Tools**  
  https://developer.android.com/tools/releases/platform-tools
  - **One UI 6.1 (Android 14) Firmware**  ⚠️
  Download via https://samfw.com
  
⚠️ **Do not proceed until you have read the [Firmware Guide](firmware.md).** ⚠️ 


## 3. Remove Accounts
**Ensure all accounts are manually removed before proceeding, failing to do so may trigger security locks or synchronization errors**
 - Open **Settings** and tap **Accounts and backup**.
 - Tap **Manage accounts**
 - Select the **accounts** listed 
 - List item
 - Tap **Remove account** and confirm.
 - Repeat for **all accounts**.
 - **For the Samsung Account:** You will usually be asked to enter your Samsung password or verify via a "one-time email" to sign out completely.

## Initialize ADB


### **WORK IN PROGRESS**

