# OpCore 0.94 - MacOS Ventura 13.5
![Captura de Tela 2023-08-20 às 12 59 23](https://github.com/tchozen/Nitro5_MacOSVentura/assets/25504430/95af5856-b3ee-4dc9-b406-83d580fd8c34)

# Hardware (Nitro5 AN515-52 Model 2018)
 i7 8750H ➰➰ (Undervolt -0.147v + TDP Increase)

 8GB 2666 + 8GB 3200 ➰➰ (2993 CL18 1T 1.25v)

 Asgard 512GB + SanDisk 240GB

UHD 630 + 1050TI 4GB

Intel AC 9560 (WIFI+BT)

# Work? not 100% but is stable

*:warning: Sleep/Wake (high battery drain in standby!)*

*:warning: WiFi (Need HeliPort.app on Ventura+)*

*:white_check_mark: iCloud Services*

*:white_check_mark: USB-C/2.0/3.0*

*:white_check_mark: iGPU (+Patch 4096)*

*:white_check_mark: TouchPad + Keyboard*

*:white_check_mark: Ethernet*

*:white_check_mark: Sound* 

*:no_entry_sign: Bluetooth (detect Broadcom vendor)*

*:no_entry_sign: AirDrop (need Bluetooth)*

*:no_entry_sign: MacOS 14 Beta (black screen bug)*

# VRam Patch

:arrow_lower_right: DeviceProperties > "framebuffer-unifiedmem" > add hex Value

![Captura de Tela 2023-08-20 às 14 37 13](https://github.com/tchozen/Nitro5_Ventura-0.94/assets/25504430/2fd1cbce-bdcc-4867-8a1d-624d1f7d0215)

1024mb : 00000040

1536mb : 00000060 

2048mb : 00000080 

2560mb : 000000A0 

3072mb : 000000C0 

3584mb : 000000E0 

4096mb : FFFFFFFF 

