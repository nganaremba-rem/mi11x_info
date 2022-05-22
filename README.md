# mi11x_info
 Requirement
  i. Custom Rom.
  ii. Firmware compatible with your custom rom android version (https://xiaomifirmwareupdater.com/firmware/)
  iii. DFE (To disable force encryption)
  iv. GApps (optional)
  v. Magisk (https://github.com/topjohnwu/Magisk/releases)
  

# Unlock Bootloader is same other.
# Flashing recovery

1. Boot into fastboot mode

2. Using platform tools 
https://dl.google.com/android/repository/platform-tools-latest-windows.zip (Windows)
https://dl.google.com/android/repository/platform-tools-latest-darwin.zip (Mac OS)
https://dl.google.com/android/repository/platform-tools-latest-linux.zip (Linux)

Command: 
"""bash
fastboot flash boot recovery.img
fastboot boot recovery.img
"""

3. Format Data

4. Flash Custom Rom along with RECOVERY again.

5. Reboot to recovery and FLASH DFE.zip

6. Wipe Data.

7. Reboot

(Boot to recovery again after first boot to flash GApps or other addon)

