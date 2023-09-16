# 64030238 Jasda
- Repo https://github.com/JASDA0000/ESP_WEBSERVER.git
# Terminal Output
```
?[0;33m--- idf_monitor on \\.\COM6 115200 ---?[0m
--- Quit: Ctrl+] | Menu: Ctrl+T | Help: Ctrl+T followed by Ctrl+H ---
ets Jul 29 2019 12:21:46

rst:0x1 (POWERON_RESET),boot:0x13 (SPI_FAST_FLASH_BOOT)
configsip: 0, SPIWP:0xee
clk_drv:0x00,q_drv:0x00,d_drv:0x00,cs0_drv:0x00,hd_drv:0x00,wp_drv:0x00
mode:DIO, clock div:2
load:0x3fff0030,len:6944
load:0x40078000,len:15500
load:0x40080400,len:3844
0x40080400: _init at ??:?

entry 0x4008064c
I (27) boot: ESP-IDF v5.0.2-dirty 2nd stage bootloader
I (27) boot: compile time 10:44:31
I (28) boot: chip revision: v3.0
I (31) boot.esp32: SPI Speed      : 40MHz
I (36) boot.esp32: SPI Mode       : DIO
I (40) boot.esp32: SPI Flash Size : 2MB
I (45) boot: Enabling RNG early entropy source...
I (50) boot: Partition Table:
I (54) boot: ## Label            Usage          Type ST Offset   Length
I (61) boot:  0 nvs              WiFi data        01 02 00009000 00006000
I (68) boot:  1 phy_init         RF data          01 01 0000f000 00001000
I (76) boot:  2 factory          factory app      00 00 00010000 00100000
I (83) boot: End of partition table
I (87) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=1e488h (124040) map
I (141) esp_image: segment 1: paddr=0002e4b0 vaddr=3ffb0000 size=01b68h (  7016) load
I (144) esp_image: segment 2: paddr=00030020 vaddr=400d0020 size=79de0h (499168) map
I (327) esp_image: segment 3: paddr=000a9e08 vaddr=3ffb1b68 size=017d4h (  6100) load
I (329) esp_image: segment 4: paddr=000ab5e4 vaddr=40080000 size=14c98h ( 85144) load
I (378) boot: Loaded app from partition at offset 0x10000
I (378) boot: Disabling RNG early entropy source...
I (390) cpu_start: Pro cpu up.
I (390) cpu_start: Starting app cpu, entry point is 0x400812b8
0x400812b8: call_start_cpu1 at C:/Espressif/frameworks/esp-idf-v5.0.2/components/esp_system/port/cpu_start.c:141

I (0) cpu_start: App cpu up.
I (406) cpu_start: Pro cpu start user code
I (406) cpu_start: cpu freq: 160000000 Hz
I (406) cpu_start: Application information:
I (411) cpu_start: Project name:     wifi_softAP
I (416) cpu_start: App version:      1
I (421) cpu_start: Compile time:     Sep 16 2023 10:44:05
I (427) cpu_start: ELF file SHA256:  24fb95371ca83058...
I (433) cpu_start: ESP-IDF:          v5.0.2-dirty
I (438) cpu_start: Min chip rev:     v0.0
I (443) cpu_start: Max chip rev:     v3.99 
I (448) cpu_start: Chip rev:         v3.0
I (453) heap_init: Initializing. RAM available for dynamic allocation:
I (460) heap_init: At 3FFAE6E0 len 00001920 (6 KiB): DRAM
I (466) heap_init: At 3FFB6F98 len 00029068 (164 KiB): DRAM
I (472) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (478) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (485) heap_init: At 40094C98 len 0000B368 (44 KiB): IRAM
I (492) spi_flash: detected chip: generic
I (496) spi_flash: flash io: dio
W (500) spi_flash: Detected size(4096k) larger than the size in the binary image header(2048k). Using the size in the binary image header.
I (514) cpu_start: Starting scheduler on PRO CPU.
I (0) cpu_start: Starting scheduler on APP CPU.
I (599) wifi softAP: ESP_WIFI_MODE_AP
I (609) wifi:wifi driver task: 3ffbefe0, prio:23, stack:6656, core=0
I (609) system_api: Base MAC address is not set
I (609) system_api: read default base MAC address from EFUSE
I (629) wifi:wifi firmware version: 57982fe
I (629) wifi:wifi certification version: v7.0
I (629) wifi:config NVS flash: enabled
I (629) wifi:config nano formating: disabled
I (639) wifi:Init data frame dynamic rx buffer num: 32
I (639) wifi:Init management frame dynamic rx buffer num: 32
I (649) wifi:Init management short buffer num: 32
I (649) wifi:Init dynamic tx buffer num: 32
I (659) wifi:Init static rx buffer size: 1600
I (659) wifi:Init static rx buffer num: 10
I (659) wifi:Init dynamic rx buffer num: 32
I (669) wifi_init: rx ba win: 6
I (669) wifi_init: tcpip mbox: 32
I (679) wifi_init: udp mbox: 6
I (679) wifi_init: tcp mbox: 6
I (679) wifi_init: tcp tx win: 5744
I (689) wifi_init: tcp rx win: 5744
I (689) wifi_init: tcp mss: 1440
I (699) wifi_init: WiFi IRAM OP enabled
I (699) wifi_init: WiFi RX IRAM OP enabled
I (709) phy_init: phy_version 4670,719f9f6,Feb 18 2021,17:07:07
I (809) wifi:mode : softAP (24:d7:eb:0e:c8:d1)
I (809) wifi:Total power save buffer number: 16
I (809) wifi:Init max length of beacon: 752/752
I (819) wifi:Init max length of beacon: 752/752
I (819) wifi softAP: wifi_init_softap finished. SSID:SSID-238 password:12345678 channel:1
?[0;33m--- idf_monitor on \\.\COM6 115200 ---?[0m
--- Quit: Ctrl+] | Menu: Ctrl+T | Help: Ctrl+T followed by Ctrl+H ---
ets Jul 29 2019 12:21:46

rst:0x1 (POWERON_RESET),boot:0x13 (SPI_FAST_FLASH_BOOT)
configsip: 0, SPIWP:0xee
clk_drv:0x00,q_drv:0x00,d_drv:0x00,cs0_drv:0x00,hd_drv:0x00,wp_drv:0x00
mode:DIO, clock div:2
load:0x3fff0030,len:6944
load:0x40078000,len:15500
load:0x40080400,len:3844
0x40080400: _init at ??:?

entry 0x4008064c
I (27) boot: ESP-IDF v5.0.2-dirty 2nd stage bootloader
I (27) boot: compile time 10:49:21
I (28) boot: chip revision: v3.0
I (31) boot.esp32: SPI Speed      : 40MHz
I (36) boot.esp32: SPI Mode       : DIO
I (40) boot.esp32: SPI Flash Size : 2MB
I (45) boot: Enabling RNG early entropy source...
I (50) boot: Partition Table:
I (54) boot: ## Label            Usage          Type ST Offset   Length
I (61) boot:  0 nvs              WiFi data        01 02 00009000 00006000
I (68) boot:  1 phy_init         RF data          01 01 0000f000 00001000
I (76) boot:  2 factory          factory app      00 00 00010000 00100000
I (83) boot: End of partition table
I (87) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=21540h (136512) map
I (145) esp_image: segment 1: paddr=00031568 vaddr=3ffb0000 size=0335ch ( 13148) load
I (151) esp_image: segment 2: paddr=000348cc vaddr=40080000 size=0b74ch ( 46924) load
I (170) esp_image: segment 3: paddr=00040020 vaddr=400d0020 size=842b8h (541368) map
I (366) esp_image: segment 4: paddr=000c42e0 vaddr=4008b74c size=0954ch ( 38220) load
I (393) boot: Loaded app from partition at offset 0x10000
I (393) boot: Disabling RNG early entropy source...
I (404) cpu_start: Pro cpu up.
I (404) cpu_start: Starting app cpu, entry point is 0x400812b8
0x400812b8: call_start_cpu1 at C:/Espressif/frameworks/esp-idf-v5.0.2/components/esp_system/port/cpu_start.c:141

I (0) cpu_start: App cpu up.
I (421) cpu_start: Pro cpu start user code
I (421) cpu_start: cpu freq: 160000000 Hz
I (421) cpu_start: Application information:
I (426) cpu_start: Project name:     simple
I (430) cpu_start: App version:      1
I (435) cpu_start: Compile time:     Sep 16 2023 10:51:43
I (441) cpu_start: ELF file SHA256:  d84fafed112fdf38...
Warning: checksum mismatch between flashed and built applications. Checksum of built application is 24fb95371ca830582e7b04d0437a3b0da2ceecc82ca3868df8d85dafd254540d
I (447) cpu_start: ESP-IDF:          v5.0.2-dirty
I (452) cpu_start: Min chip rev:     v0.0
I (457) cpu_start: Max chip rev:     v3.99 
I (462) cpu_start: Chip rev:         v3.0
I (467) heap_init: Initializing. RAM available for dynamic allocation:
I (474) heap_init: At 3FFAE6E0 len 00001920 (6 KiB): DRAM
I (480) heap_init: At 3FFB6FC8 len 00029038 (164 KiB): DRAM
I (486) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (492) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (499) heap_init: At 40094C98 len 0000B368 (44 KiB): IRAM
I (507) spi_flash: detected chip: generic
I (510) spi_flash: flash io: dio
W (514) spi_flash: Detected size(4096k) larger than the size in the binary image header(2048k). Using the size in the binary image header.
I (528) cpu_start: Starting scheduler on PRO CPU.
I (0) cpu_start: Starting scheduler on APP CPU.
I (615) example_connect: Start example_connect.
I (625) wifi:wifi driver task: 3ffbec20, prio:23, stack:6656, core=0
I (625) system_api: Base MAC address is not set
I (625) system_api: read default base MAC address from EFUSE
I (655) wifi:wifi firmware version: 57982fe
I (655) wifi:wifi certification version: v7.0
I (655) wifi:config NVS flash: enabled
I (655) wifi:config nano formating: disabled
I (655) wifi:Init data frame dynamic rx buffer num: 32
I (665) wifi:Init management frame dynamic rx buffer num: 32
I (665) wifi:Init management short buffer num: 32
I (675) wifi:Init dynamic tx buffer num: 32
I (675) wifi:Init static rx buffer size: 1600
I (675) wifi:Init static rx buffer num: 10
I (685) wifi:Init dynamic rx buffer num: 32
I (685) wifi_init: rx ba win: 6
I (695) wifi_init: tcpip mbox: 32
I (695) wifi_init: udp mbox: 6
I (695) wifi_init: tcp mbox: 6
I (705) wifi_init: tcp tx win: 5744
I (705) wifi_init: tcp rx win: 5744
I (715) wifi_init: tcp mss: 1440
I (715) wifi_init: WiFi IRAM OP enabled
I (715) wifi_init: WiFi RX IRAM OP enabled
I (725) phy_init: phy_version 4670,719f9f6,Feb 18 2021,17:07:07
I (825) wifi:mode : sta (24:d7:eb:0e:c8:d0)
I (825) wifi:enable tsf
I (825) example_connect: Connecting to Solomon...
I (835) example_connect: Waiting for IP(s)
I (3245) wifi:new:<6,0>, old:<1,0>, ap:<255,255>, sta:<6,0>, prof:1
I (3915) wifi:state: init -> auth (b0)
I (3925) wifi:state: auth -> assoc (0)
I (3925) wifi:state: assoc -> run (10)
I (3955) wifi:connected with Solomon, aid = 1, channel 6, BW20, bssid = ce:f3:b2:ed:8e:39
I (3955) wifi:security: WPA2-PSK, phy: bgn, rssi: -43
I (3965) wifi:pm start, type: 1

I (3985) wifi:AP's beacon interval = 102400 us, DTIM period = 1
I (4475) wifi:<ba-add>idx:0 (ifx:0, ce:f3:b2:ed:8e:39), tid:0, ssn:2, winSize:64
I (5465) esp_netif_handlers: example_netif_sta ip: 172.20.10.10, mask: 255.255.255.240, gw: 172.20.10.1
I (5465) example_connect: Got IPv4 event: Interface "example_netif_sta" address: 172.20.10.10
I (5615) example_connect: Got IPv6 event: Interface "example_netif_sta" address: fe80:0000:0000:0000:26d7:ebff:fe0e:c8d0, type: ESP_IP6_ADDR_IS_LINK_LOCAL
I (5615) example_common: Connected to example_netif_sta
I (5625) example_common: - IPv4 address: 172.20.10.10,
I (5625) example_common: - IPv6 address: fe80:0000:0000:0000:26d7:ebff:fe0e:c8d0, type: ESP_IP6_ADDR_IS_LINK_LOCAL
I (5635) example: Starting server on port: '80'
I (5645) example: Registering URI handlers
To exit from IDF monitor please use "Ctrl+]". Alternatively, you can use Ctrl-T Ctrl-X to exit.
I (20765) example: Found header => Host: 172.20.10.10
I (20775) example: Request headers lost


```