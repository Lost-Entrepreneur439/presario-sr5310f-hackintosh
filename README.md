# presario-sr5310f-hackintosh
Snow Leopard Hackintosh EFI for the Compaq Presario SR5310F

**WARNING! Sleep, reset and NVRAM are currently not working.**

This is a macOS EFI for the Compaq Presario SR5310F. Snow Leopard compatible

![ftyu](https://github.com/user-attachments/assets/8ece0ab1-b92d-487f-868a-a8c95da0ea6b)

# System Specs:

* CPU: Intel Pentium Dual-Core E2140
* GPU: Intel GMA 950
* RAM: 1GB DDR2 RAM
* Model: Compaq Presario SR5310F
* Audio: Realtek ALC888
* Ethernet: Realtek RTL8139

Follow the "Downloading macOS section in the Dortania guide to get macOS. **Support will not be offered if you get macOS from any other source.** https://dortania.github.io/OpenCore-Install-Guide/installer-guide/mac-install-dmg.html

# Set BIOS settings as follows

* Authentication -> Secure Boot -> Disabled
* Boot Options -> Launch CSM -> Never

# Credits

* [Acidanthera](https://github.com/acidanthera) -- Made OpenCore, AppleALC, BlueToolFixup, Lilu, VirtualSMC and WhateverGreen
* [OpenIntelWireless](https://github.com/OpenIntelWireless) -- Made airportitlwm
* [FireWolf](https://github.com/0xFireWolf) -- Made RealtekCardReader
* [Laura Müller](https://github.com/Mieze) -- Made RealtekRTL8111 
* [USBToolBox](https://github.com/USBToolBox) -- Made USBToolBox
* [Apple](https://www.apple.com/ca/) -- Made macOS
* [Acer](https://www.acer.com/us-en) -- Made the Aspire TC-780
* [Dortania](https://github.com/dortania) -- Made the OpenCore install guide which was used to make this EFI
* [CorpNewt](https://github.com/corpnewt) -- Helped me fix graphics
* MeGaLoDoN (No GitHub or website) -- Helped me fix Bluetooth
