# Hackintosh Nitro5 - OpCore 0.94


# Hardware
i7 8750H - 6C/12T (undervolt -0.147v)

8GB XPG 2666 + 8GB Kingston 3200 (@ 2993mhz 1.25v)

Asgard NVME 512GB + SanDisk Plus 240GB

Coffee Lake UHD 630 + 1050TI 

Intel AC 9560 (WIFI + BT)


# Funciona? 99% porem estável 24/7

*MacOS 14 Beta Off - (black screen bug)*

*iCloud Services Ok (Certifique de gerar uma nova SMBIOS!)*

*iGPU Ok (+Patch 4096mb)*

*USB-C/2.0/3.0 Ok (Need mapUSB For BT)*

*BT Off (detect Broadcom vendor)*

*AirDrop Off (need BT)*

*WiFi Ok (Need HeliPort on Ventura+)*

*Sleep/Wake ok (high battery drain standby!)*

*TouchPad + Keyboard Ok*

*Ethernet Ok*

*Sound Ok* 


# VRam Patch

DeviceProperties > "framebuffer-unifiedmem" > Hex DATA

00000040 = 1024MB

00000060 = 1536MB

00000080 = 2048MB

000000A0 = 2560MB

000000C0 = 3072MB

000000E0 = 3584MB

FFFFFFFF = 4096MB

