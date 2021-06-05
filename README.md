
# Dell Inspiron 15 3567 macOS OpenCore EFI

This repository and project hosts the files necessary to boot macOS Big Sur successfully on the Dell Inspiron 15 3567 notebook.

## Acknowledgements

 - [Core x86 Group & Team](https://discord.corex86.com)
 - [Dortania Team for their OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)
 
  
## Authors

- [@osx86_iJB](https://www.github.com/osx86-ijb)
  

## Deployment

To deploy this project properly, please obtain the EFI folder from this repository, edit the config.plist to generate new serial number, rom, UUID, etcetera, then save config.plist, follow the Dortania OpenCore Install Guide to the fullest, and then place the files onto the appropriate ESP EFI partition in order to boot using OpenCore bootloader and proceed with your installation of macOS / post setup of your machine.
  
## Documentation

```The hardware used in this build is as follows:```

- AUDIO CHIPSET: Realtek ALC256 + Intel HDMI Audio + USB DAC
- CPU: Intel 7th Generation Core i3 7100u @ 2.4GHz
- GPU: Intel HD Graphics 620 iGPU
- LAN CHIPSET: Realtek RTL8106e Gigabit Ethernet
- RAM: 32GB DDR4 2666MHz Crucial 
- STORAGE / SSD: TEAMGROUP L5 3D 1TB + Much More Other Storage
- WIFI + BLUETOOTH = Dell DW1560 (Broadcom BCM4352z 802.11ac + BT 4.0)