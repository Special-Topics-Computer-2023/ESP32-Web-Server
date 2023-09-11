# 64030161 Rachata
- Repo https://github.com/RachataS/ESP-Web-Server.git

## Web

![Screenshot 2566-09-11 at 17 30 52](https://github.com/RachataS/ESP-Web-Server/assets/115066261/b800809a-ad3a-4470-9501-5a92648ab5c5)

## Terminal output

```css
entry 0x40080698
I (27) boot: ESP-IDF v4.4.5-dirty 2nd stage bootloader
I (27) boot: compile time 17:19:49
I (27) boot: chip revision: v3.0
I (31) boot.esp32: SPI Speed      : 40MHz
I (36) boot.esp32: SPI Mode       : DIO
I (40) boot.esp32: SPI Flash Size : 4MB
I (45) boot: Enabling RNG early entropy source...
I (50) boot: Partition Table:
I (54) boot: ## Label            Usage          Type ST Offset   Length
I (61) boot:  0 nvs              WiFi data        01 02 00009000 00006000
I (68) boot:  1 phy_init         RF data          01 01 0000f000 00001000
I (76) boot:  2 factory          factory app      00 00 00010000 00100000
I (83) boot: End of partition table
I (88) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=16b44h ( 92996) map
I (130) esp_image: segment 1: paddr=00026b6c vaddr=3ffb0000 size=03038h ( 12344) load
I (135) esp_image: segment 2: paddr=00029bac vaddr=40080000 size=0646ch ( 25708) load
I (146) esp_image: segment 3: paddr=00030020 vaddr=400d0020 size=7a558h (501080) map
I (328) esp_image: segment 4: paddr=000aa580 vaddr=4008646c size=0e44ch ( 58444) load
I (362) boot: Loaded app from partition at offset 0x10000
I (362) boot: Disabling RNG early entropy source...
I (373) cpu_start: Pro cpu up.
I (374) cpu_start: Starting app cpu, entry point is 0x4008117c
0x4008117c: call_start_cpu1 at /Users/rachatasupanurak/esp/esp-idf/components/esp_system/port/cpu_start.c:147

I (0) cpu_start: App cpu up.
I (390) cpu_start: Pro cpu start user code
I (390) cpu_start: cpu freq: 160000000
I (390) cpu_start: Application information:
I (394) cpu_start: Project name:     ESP-Web-Server
I (400) cpu_start: App version:      946c27f
I (405) cpu_start: Compile time:     Sep 11 2023 17:20:15
I (411) cpu_start: ELF file SHA256:  44d943de3a78787f...
I (417) cpu_start: ESP-IDF:          v4.4.5-dirty
I (422) cpu_start: Min chip rev:     v0.0
I (427) cpu_start: Max chip rev:     v3.99
I (432) cpu_start: Chip rev:         v3.0
I (437) heap_init: Initializing. RAM available for dynamic allocation:
I (444) heap_init: At 3FFAE6E0 len 00001920 (6 KiB): DRAM
I (450) heap_init: At 3FFB6CC8 len 00029338 (164 KiB): DRAM
I (456) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (463) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (469) heap_init: At 400948B8 len 0000B748 (45 KiB): IRAM
I (477) spi_flash: detected chip: generic
I (480) spi_flash: flash io: dio
I (485) cpu_start: Starting scheduler on PRO CPU.
I (0) cpu_start: Starting scheduler on APP CPU.
I (582) wifi:wifi driver task: 3ffbee18, prio:23, stack:6656, core=0
I (582) system_api: Base MAC address is not set
I (582) system_api: read default base MAC address from EFUSE
I (602) wifi:wifi firmware version: 0f80fa0
I (602) wifi:wifi certification version: v7.0
I (602) wifi:config NVS flash: enabled
I (602) wifi:config nano formating: disabled
I (612) wifi:Init data frame dynamic rx buffer num: 32
I (612) wifi:Init management frame dynamic rx buffer num: 32
I (622) wifi:Init management short buffer num: 32
I (622) wifi:Init dynamic tx buffer num: 32
I (632) wifi:Init static rx buffer size: 1600
I (632) wifi:Init static rx buffer num: 10
I (632) wifi:Init dynamic rx buffer num: 32
I (642) wifi_init: rx ba win: 6
I (642) wifi_init: tcpip mbox: 32
I (652) wifi_init: udp mbox: 6
I (652) wifi_init: tcp mbox: 6
I (652) wifi_init: tcp tx win: 5744
I (662) wifi_init: tcp rx win: 5744
I (662) wifi_init: tcp mss: 1440
I (672) wifi_init: WiFi IRAM OP enabled
I (672) wifi_init: WiFi RX IRAM OP enabled
I (682) example_connect: Connecting to Myangle_2.4G...
I (682) phy_init: phy_version 4670,719f9f6,Feb 18 2021,17:07:07
I (782) wifi:mode : sta (24:d7:eb:0e:cb:20)
I (792) wifi:enable tsf
I (792) example_connect: Waiting for IP(s)
I (3202) wifi:new:<5,0>, old:<1,0>, ap:<255,255>, sta:<5,0>, prof:1
I (3942) wifi:state: init -> auth (b0)
I (3942) wifi:state: auth -> assoc (0)
I (3952) wifi:state: assoc -> run (10)
I (3972) wifi:connected with Myangle_2.4G, aid = 52, channel 5, BW20, bssid = 44:67:47:5f:fe:b4
I (3972) wifi:security: WPA2-PSK, phy: bgn, rssi: -86
I (3972) wifi:pm start, type: 1

I (4082) wifi:AP's beacon interval = 102400 us, DTIM period = 1
I (5572) example_connect: Got IPv6 event: Interface "example_connect: sta" address: fe80:0000:0000:0000:26d7:ebff:fe0e:cb20, type: ESP_IP6_ADDR_IS_LINK_LOCAL
I (7982) esp_netif_handlers: example_connect: sta ip: 192.168.1.179, mask: 255.255.255.0, gw: 192.168.1.1
I (7982) example_connect: Got IPv4 event: Interface "example_connect: sta" address: 192.168.1.179
I (7992) example_connect: Connected to example_connect: sta
I (7992) example_connect: - IPv4 address: 192.168.1.179
I (8002) example_connect: - IPv6 address: fe80:0000:0000:0000:26d7:ebff:fe0e:cb20, type: ESP_IP6_ADDR_IS_LINK_LOCAL
I (8012) example: Starting server on port: '80'
I (8022) example: Registering URI handlers
W (10592) httpd_uri: httpd_uri: URI '/' not found
W (10602) httpd_txrx: httpd_resp_send_err: 404 Not Found - This URI does not exist
I (10622) wifi:<ba-add>idx:0 (ifx:0, 44:67:47:5f:fe:b4), tid:0, ssn:1007, winSize:64
W (10732) httpd_uri: httpd_uri: URI '/favicon.ico' not found
W (10732) httpd_txrx: httpd_resp_send_err: 404 Not Found - This URI does not exist
I (21552) example: Found header => Host: 192.168.1.179
I (21562) example: Request headers lost
```
