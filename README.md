# Hackintosh
* [English](https://github.com/Xin9912/Hackintosh/blob/master/README.md)
* [简体中文](https://github.com/Xin9912/Hackintosh/blob/master/README_cn.md)
&emsp;
## Descriptions <br>
* It's EFI files to hackintosh for laptop Hasee Z7M-KP7GT. It may work well util macOS(Catalina)10.15.5. And if you have similar configurations to mine, you could try it. Well, here is my laptop config: <br>

| Devices | Model |
| ---- | ---- |
| Laptop model| Hasee Z7M-KP7GT |
| Motherboard|HM175 series |
| CPU | Intel i7-7700HQ |
| IGPU | UHD630 |
| DGPU | Nvidia GTX 1050ti|
| Audio | ALC269VC |
| wireless card | Brcm943224 |

## Attention <br>
* I have configured OC and it works well on my laptop.Dsiable PS2 kexts in config and place them in S/L/E, the laptop will start faster than with them. So I made a config_ps2_disable to disable these kexts in EFI. I think I will use opencore to boot system rather than Clover. <br>
* Clover works well on my laptop, but the keyboard blacklight setting can't work if shutdown your laptop and then boot. <br>
* **Note**:I removed SMBIOS settings in config.plist. So you should change or set the SMBIOS settings in the config.plist which you choose. <br>

| Bootloader | macOS version |
| ---- | ---- |
| Opencore 0.5.9 Realease | macOS Catalina 10.15.5 |
|Clover 5112 (Stop Updating) | macOS Catalina 10.15.5 |
