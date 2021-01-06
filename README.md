# Hackintosh on ThinkPadT480s | Clover and OpenCore


## Contact me
[![Telegram](https://img.shields.io/badge/Chat_on-Telegram-blue.svg)](https://t.me/opf_lep)

## Big Sur 11.1 / OpenCore 0.6.4 / DW1560

- Updated newest kexts, so far no issues
- Config AirportBrcmFixup.kext with DW1560
- USBPorts.kext alternate USBInjectAll.kext: Disable Intergrated IR Camera
- Disable Touchscreen for battery optimization

## Catalina 10.15.6 / OpenCore 0.6.4 / DW1560

- Fixed Bluetooth/AirDrop greyed out by patching USB Port:
	- Mapping in SSDT-EC.aml.
	- USBMap.kext is disabled
- Fixed battery icon with SSDT-Battery.aml
- Bluetooth/Wifi supported on DW1560 with Brcm 2.5.5 kext pack

## Catalina 10.15.6 / Clover r5122 / DW1560

- Fixed Shutdown/Restart Error with FixShutdownßß_0004 option
- Fixed Bluetooth/AirDrop greyed out by patching USB Port 
- Bluetooth/Wifi supported on DW1560 with Brcm kext pack

### Other Reasources

- https://github.com/EETagent/T480-OpenCore-Hackintosh
- https://github.com/mohamedspicer/hackintosh-T480s
- https://github.com/yqsas/Hackintosh-T480s
- https://github.com/RehabMan/OS-X-BrcmPatchRAM


  *All credit goes to all of those guys*
