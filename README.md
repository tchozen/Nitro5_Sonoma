# OpCore 0.94 - MacOS Ventura 13.5
![Captura de Tela 2023-08-20 às 15 20 08](https://github.com/tchozen/Nitro5_Ventura-0.94/assets/25504430/6e475c16-ea5b-499c-89cb-e36e15c26f48)

# Nitro5 AN515-52
i7 8750H (@Undervolt -0.147v)

8GB XPG 2666 + 8GB Kingston 3200 (@2993mhz 1.25v)

Asgard NVME 512GB + SanDisk Plus 240GB

Intel UHD 630 + 1050TI 

Intel AC 9560 (WIFI + BT)


# Work? 99% yes

*:warning:iCloud Services (Certifique de gerar uma nova SMBIOS!)*

*:warning:Sleep/Wake (high battery drain standby!)*

*:warning:WiFi (Need HeliPort on Ventura+)*

*:warning:USB-C/2.0/3.0 (Need mapUSB For BT)*

*:white_check_mark:iGPU (+Patch 4096mb)*

*:white_check_mark:TouchPad + Keyboard*

*:white_check_mark:Ethernet*

*:white_check_mark:Sound* 

*:no_entry_sign:BlueTooth (detect Broadcom vendor)*

*:no_entry_sign:AirDrop (need BlueTooth)*

*:no_entry_sign:MacOS 14 Beta (black screen bug)*

# VRam Patch

DeviceProperties > "framebuffer-unifiedmem" > Hex DATA

![Captura de Tela 2023-08-20 às 14 37 13](https://github.com/tchozen/Nitro5_Ventura-0.94/assets/25504430/2fd1cbce-bdcc-4867-8a1d-624d1f7d0215)

1024mb : 00000040

1536mb : 00000060 

2048mb : 00000080 

2560mb : 000000A0 

3072mb : 000000C0 

3584mb : 000000E0 

4096mb : FFFFFFFF 

