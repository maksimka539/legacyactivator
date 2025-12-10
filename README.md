# iOS 5–10 Hacktivation Tool

**Author:** [maksimka539](https://github.com/maksimka539)\
**Compatibility:** iOS 5.0 – 10.3.4 (32-bit devices only)\
**Purpose:** Bypass iCloud activation screen using SSH Ramdisk method.

---

## What is this?

This tool is designed for **iCloud-locked devices** running iOS 5–10. (64bit not tested)\
It uses an **SSH Ramdisk**, loaded via [Legacy iOS Kit](https://github.com/LukeZGD/Legacy-iOS-Kit), to patch system files and simulate activation.\
No activation files are required — everything is done directly via SSH!

## Requirements

### You need
 **Legacy iOS Kit**\
   Used to create and launch the SSH Ramdisk.\
   → [https://github.com/LukeZGD/Legacy-iOS-Kit](https://github.com/LukeZGD/Legacy-iOS-Kit)

---

## Usage Instructions

1. **Download and unzip the tool:**

2. **Run SSH Ramdisk using Legacy iOS Kit**\
   The device must be in **SSH mode** (port 6414). Remember to click **Connect to SSH** and type mount.sh in LIK window.\
   See: [Legacy iOS Kit SSH Ramdisk Guide](https://github.com/LukeZGD/Legacy-iOS-Kit/wiki/SSH-Ramdisk)


3. **Without closing the LIK window**, open a new terminal window, navigate to the folder containing the script, and run it:

```bash
./hacktivate.sh
```

---

## Important 

- This tool **does not remove iCloud lock**, it only activate and bypasses the activation screen. Signal will not work.

---

## Credits & Contact

Author: [**@maksimka539**](https://github.com/maksimka539)\
**Donate:** \
**TONCOIN:** UQB97hrGbiF7my3BykAm-QNWzhFamBLtHCB6myhygLS7M9t3 \
**Ozon банк:** 2204320377216017 \

Credits to [**iPh0ne4s**](https://github.com/iPh0ne4s) for the [**lockdownd**](https://github.com/iPh0ne4s/iOS-5-6-Hacktivation) file.

Feel free to open Issues or Pull Requests for suggestions and improvements.

