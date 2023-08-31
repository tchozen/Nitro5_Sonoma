# OpenCore 0.94 - Success Sonoma Beta 5 :partying_face: :partying_face:


   ![Captura de Tela 2023-08-22 às 00 21 42](https://github.com/tchozen/Nitro5_MacOSVentura/assets/25504430/43b82d68-173c-4d80-b584-2ec38653932d)


# Nitro 5 2018 an515-52
 i7 8750h  ➰➰ (Undervolt + TDP unlock)

 8GB 2666 + 8GB 3200  ➰➰ (2993mhz 1.25v)

 Asgard 512GB + SanDisk 240GB

Coffee Lake UHD 630 + 1050TI 4GB

Intel AC 9560 (WiFi+BT)

**this efi has set-up skip boot selector on opencore, is booting first macos in list automatically **
# Work? 

*:white_check_mark: Sleep/Wake*

*:white_check_mark: WiFi*

*:white_check_mark: iCloud Services*

*:white_check_mark: USB-C/2.0/3.0*

*:white_check_mark: iGPU (+Patch 4096)*

*:white_check_mark: TouchPad + Keyboard*

*:white_check_mark: Ethernet*

*:white_check_mark: Sound* 

*:no_entry_sign: Bluetooth (detect Broadcom vendor)*

*:no_entry_sign: AirDrop (need Bluetooth)*

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

