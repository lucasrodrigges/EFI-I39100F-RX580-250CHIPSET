# EFI 
EFI based on [Gabriel Luchina's repository](https://github.com/luchina-gabriel/BASE-EFI-INTEL-DESKTOP-9THGEN-COFFEE-LAKE-REFRESH).  

 * You'll need to replace `PlatformInfo` in `config.plist` with [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) information, using [ProperTree](https://github.com/corpnewt/ProperTree). 
 * USB Mapping (no 3.0 ports yet). 
 * I've created the layout of my codec audio (Realtek ALC662) in `DeviceProperties`
 * I had to use [RealtekRTL8100.kext](https://www.insanelymac.com/forum/files/file/259-realtekrtl8100-binary/) for ethernet (already included), but depends on your network adapter. 
 * I was using `iMac19,1` in SMBios, but the keyboard layout didn't match mine (PT-BR ABNT2), now I'm using `iMacPro1,1`.

# Setup

**Plataform: Desktop | Intel 9th gen** 
| Type | Item |
| ---- | ---- |
| CPU | i3 9100F |
| Motherboard | Jginyue b250 |
| RAM | 2x 8gb 2666Mhz |
| GPU | Rx 570 8Gb |
| SMBios | iMacPro1,1 |
| MacOS | Catalina - BigSur - Monterey - Ventura |
| OpenCore | 0.9.2 |

## Boot Args
```
npci=0x2000
```

# References
[Gabriel Luchina's Tutorial (PT-BR)](https://youtu.be/PlKEHa0zeSk)

[Gabriel Luchina's Repository](https://github.com/luchina-gabriel)

[Dortania's OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)

[Universo Hackintosh (Discord)](https://discord.com/channels/887798875069505587/927544946553147433)
