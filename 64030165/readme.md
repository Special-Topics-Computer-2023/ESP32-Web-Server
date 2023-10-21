# 64030165 Ratchanon
- Repo https://github.com/RatchanonBusaracome/ESP32-Web-Server.git

## Web

![Screenshot 2023-10-21 191343](https://github.com/RatchanonBusaracome/ESP32-Web-Server/assets/115066405/2898031e-834e-4975-905e-8446f03bdfef)

## Terminal output

```css
I (27) boot: ESP-IDF v5.0.2-dirty 2nd stage bootloader
I (27) boot: compile time 18:57:14
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
I (87) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=21520h (136480) map
I (145) esp_image: segment 1: paddr=00031548 vaddr=3ffb0000 size=0335ch ( 13148) load
I (151) esp_image: segment 2: paddr=000348ac vaddr=40080000 size=0b76ch ( 46956) load
I (170) esp_image: segment 3: paddr=00040020 vaddr=400d0020 size=842bch (541372) map
I (366) esp_image: segment 4: paddr=000c42e4 vaddr=4008b76c size=0952ch ( 38188) load
I (393) boot: Loaded app from partition at offset 0x10000
I (393) boot: Disabling RNG early entropy source...
I (404) cpu_start: Pro cpu up.
I (404) cpu_start: Starting app cpu, entry point is 0x400812b8
0x400812b8: call_start_cpu1 at F:/Espressif/frameworks/esp-idf-v5.0.2/components/esp_system/port/cpu_start.c:141

I (0) cpu_start: App cpu up.
I (421) cpu_start: Pro cpu start user code
I (421) cpu_start: cpu freq: 160000000 Hz
I (421) cpu_start: Application information:
I (426) cpu_start: Project name:     simple
I (430) cpu_start: App version:      1
I (435) cpu_start: Compile time:     Oct 21 2023 19:08:38
I (441) cpu_start: ELF file SHA256:  ebea5421f4230981...
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
I (506) spi_flash: detected chip: generic
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
I (655) wifi:Init management frame dynamic rx buffer num: 32
I (665) wifi:Init management short buffer num: 32
I (665) wifi:Init dynamic tx buffer num: 32
I (675) wifi:Init static rx buffer size: 1600
I (675) wifi:Init static rx buffer num: 10
I (685) wifi:Init dynamic rx buffer num: 32
I (685) wifi_init: rx ba win: 6
I (685) wifi_init: tcpip mbox: 32
I (695) wifi_init: udp mbox: 6
I (695) wifi_init: tcp mbox: 6
I (705) wifi_init: tcp tx win: 5744
I (705) wifi_init: tcp rx win: 5744
I (705) wifi_init: tcp mss: 1440
I (715) wifi_init: WiFi IRAM OP enabled
I (715) wifi_init: WiFi RX IRAM OP enabled
I (725) phy_init: phy_version 4670,719f9f6,Feb 18 2021,17:07:07
I (835) wifi:mode : sta (94:b5:55:f8:30:00)
I (835) wifi:enable tsf
I (835) example_connect: Connecting to Koowithyou...
I (835) example_connect: Waiting for IP(s)
I (3245) wifi:new:<6,0>, old:<1,0>, ap:<255,255>, sta:<6,0>, prof:1
I (3255) wifi:state: init -> auth (b0)
I (4785) wifi:state: auth -> assoc (0)
E (4795) wifi:Association refused temporarily, comeback time 200 mSec
I (4995) wifi:state: assoc -> assoc (0)
E (4995) wifi:Association refused temporarily, comeback time 200 mSec
I (5195) wifi:state: assoc -> assoc (0)
E (5205) wifi:Association refused temporarily, comeback time 200 mSec
I (5405) wifi:state: assoc -> assoc (0)
E (5405) wifi:Association refused temporarily, comeback time 200 mSec
I (5605) wifi:state: assoc -> assoc (0)
E (5615) wifi:Association refused temporarily, comeback time 200 mSec
I (5815) wifi:state: assoc -> assoc (0)
E (5825) wifi:Association refused temporarily, comeback time 200 mSec
I (6025) wifi:state: assoc -> assoc (0)
E (6035) wifi:Association refused temporarily, comeback time 200 mSec
I (6235) wifi:state: assoc -> assoc (0)
E (6235) wifi:Association refused temporarily, comeback time 200 mSec
I (6435) wifi:state: assoc -> assoc (0)
E (6445) wifi:Association refused temporarily, comeback time 200 mSec
I (6645) wifi:state: assoc -> assoc (0)
E (6645) wifi:Association refused temporarily, comeback time 200 mSec
I (6845) wifi:state: assoc -> assoc (0)
E (6855) wifi:Association refused temporarily, comeback time 200 mSec
I (7055) wifi:state: assoc -> assoc (0)
E (7075) wifi:Association refused temporarily, comeback time 200 mSec
I (7275) wifi:state: assoc -> assoc (0)
E (7285) wifi:Association refused temporarily, comeback time 200 mSec
I (7485) wifi:state: assoc -> assoc (0)
I (7495) wifi:state: assoc -> run (10)
I (17495) wifi:state: run -> init (cc00)
I (17495) wifi:new:<6,0>, old:<6,0>, ap:<255,255>, sta:<6,0>, prof:1
I (17495) example_connect: Wi-Fi disconnected, trying to reconnect...
I (19915) example_connect: Wi-Fi disconnected, trying to reconnect...
I (22325) wifi:new:<6,0>, old:<6,0>, ap:<255,255>, sta:<6,0>, prof:1
I (22325) wifi:state: init -> auth (b0)
I (23875) wifi:state: auth -> assoc (0)
I (23875) wifi:state: assoc -> run (10)
I (23915) wifi:connected with Koowithyou, aid = 2, channel 6, BW20, bssid = 26:d6:e0:13:61:cc
I (23915) wifi:security: WPA3-SAE, phy: bgn, rssi: -57
I (23925) wifi:pm start, type: 1

I (23935) wifi:<ba-add>idx:0 (ifx:0, 26:d6:e0:13:61:cc), tid:0, ssn:2, winSize:64
I (23985) wifi:AP's beacon interval = 102400 us, DTIM period = 3
I (24925) esp_netif_handlers: example_netif_sta ip: 172.20.10.13, mask: 255.255.255.240, gw: 172.20.10.1
I (24925) example_connect: Got IPv4 event: Interface "example_netif_sta" address: 172.20.10.13
I (25615) example_connect: Got IPv6 event: Interface "example_netif_sta" address: fe80:0000:0000:0000:96b5:55ff:fef8:3000, type: ESP_IP6_ADDR_IS_LINK_LOCAL
I (25615) example_common: Connected to example_netif_sta
I (25625) example_common: - IPv4 address: 172.20.10.13,
I (25625) example_common: - IPv6 address: fe80:0000:0000:0000:96b5:55ff:fef8:3000, type: ESP_IP6_ADDR_IS_LINK_LOCAL
I (25635) example: Starting server on port: '80'
I (25645) example: Registering URI handlers
W (40605) httpd_uri: httpd_uri: URI '/' not found
W (40605) httpd_txrx: httpd_resp_send_err: 404 Not Found - Nothing matches the given URI
I (46125) example: Found header => Host: 172.20.10.13
I (46135) example: Request headers lost

```css
