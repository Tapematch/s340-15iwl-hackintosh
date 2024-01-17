
# Lenovo IdeaPad S340-15IWL Hackintosh (WIP)

Configuration for a Hackintosh on a Lenovo IdeaPad S340-15IWL running macOS Sonoma using OpenCore 0.9.7

### Hardware
- CPU: Intel i7-8565U (Whiskey Lake Q3 2018)
- GPU: Intel UHD 620 / MX230
- Chipset: Intel Whiskey Lake-U IMC
- Input: I2C
- Audio Codec: Intel Cannon Point-LP PCH - cAVS
- Network Controller: Dell DW1820a BCM94350ZAE (swapped)
- SSD: WD SN730 512GB (swapped)

### Installation process
1. Change SSD and Network Card
2. Make installer with macOS Big Sur (Ventura Installer did not recognize the SSD)
	https://dortania.github.io/OpenCore-Install-Guide/installer-guide/
3. Create EFI with Dortania´s install guide and SSDTTime
3. Update to Sonoma
4. Fix wifi
	https://elitemacx86.com/threads/how-to-fix-broadcom-wifi-on-macos-sonoma-and-later.1415/

### Working
- Screen with smooth brightness setting
- Wifi
- Bluetooth
- Airdrop
- Audio
- Microphone
- Sleep
- USB Ports
- Battery status

### Not working
- dGPU
- Webcam
- Fingerprint Scanner
- Sidecar
- Unlock with Apple Watch

![info screenshot](https://github.com/Tapematch/s340-15iwl-hackintosh/blob/06ccb9acb2d8914fa37e94ea305831a79705f997/Screenshots/info.png)
![settings screenshot](https://github.com/Tapematch/s340-15iwl-hackintosh/blob/06ccb9acb2d8914fa37e94ea305831a79705f997/Screenshots/settings.png)
