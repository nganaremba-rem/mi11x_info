# mi11x_info

## Requirement
>1. Custom Rom.
>2. Firmware compatible with your custom rom android version (https://xiaomifirmwareupdater.com/firmware/)
>3. DFE (To disable force encryption)
>4. GApps (optional)
>5. Magisk (https://github.com/topjohnwu/Magisk/releases)
  

## Unlock Bootloader is same as other device .
## Flashing recovery

>1. Boot into fastboot mode

>2. Using platform tools 

>https://dl.google.com/android/repository/platform-tools-latest-windows.zip (Windows)

>https://dl.google.com/android/repository/platform-tools-latest-darwin.zip (Mac OS)

>https://dl.google.com/android/repository/platform-tools-latest-linux.zip (Linux)

> ###Command: 
```bash
fastboot flash boot recovery.img
fastboot boot recovery.img
```
## Flashing ROM

> 1. Format Data
> 2. Flash Custom Rom along with RECOVERY again.
> 3. Reboot to recovery and FLASH DFE.zip
> 4. Wipe Data.
> 5. Reboot

(Boot to recovery again after first boot to flash GApps or other addon)

