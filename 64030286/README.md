Web
![image](https://github.com/Special-Topics-Computer-2023/ESP32-Web-Server/assets/115067018/36e16e3c-22e3-4264-a03d-7ad431fe06b6)

Terminal output



			
	entry 0x4008064c
	I (27) boot: ESP-IDF v5.0.2-dirty 2nd stage bootloader
	I (27) boot: compile time 09:58:24
	I (27) boot: chip revision: v1.0
	I (30) boot.esp32: SPI Speed      : 40MHz
	I (35) boot.esp32: SPI Mode       : DIO
	I (40) boot.esp32: SPI Flash Size : 2MB
	I (44) boot: Enabling RNG early entropy source...
	I (50) boot: Partition Table:
	I (53) boot: ## Label            Usage          Type ST Offset   Length
	I (60) boot:  0 nvs              WiFi data        01 02 00009000 00006000
	I (68) boot:  1 phy_init         RF data          01 01 0000f000 00001000
	I (75) boot:  2 factory          factory app      00 00 00010000 00100000
	I (83) boot: End of partition table
	I (87) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=21500h (136448) map
	I (145) esp_image: segment 1: paddr=00031528 vaddr=3ffb0000 size=0335ch ( 13148) load
	I (150) esp_image: segment 2: paddr=0003488c vaddr=40080000 size=0b78ch ( 46988) load
	I (170) esp_image: segment 3: paddr=00040020 vaddr=400d0020 size=842e0h (541408) map
	I (366) esp_image: segment 4: paddr=000c4308 vaddr=4008b78c size=0950ch ( 38156) load
	I (392) boot: Loaded app from partition at offset 0x10000
	I (392) boot: Disabling RNG early entropy source...
	I (404) cpu_start: Pro cpu up.
	I (404) cpu_start: Starting app cpu, entry point is 0x400812b8
	0x400812b8: call_start_cpu1 at C:/Espressif/frameworks/esp-idf-v5.0.2/components/esp_system/port/cpu_start.c:141
	
	I (0) cpu_start: App cpu up.
	I (420) cpu_start: Pro cpu start user code
	I (420) cpu_start: cpu freq: 160000000 Hz
	I (420) cpu_start: Application information:
	I (425) cpu_start: Project name:     simple
	I (430) cpu_start: App version:      1
	I (434) cpu_start: Compile time:     Nov 10 2023 10:01:04
	I (440) cpu_start: ELF file SHA256:  eb15bada68890f36...
	I (446) cpu_start: ESP-IDF:          v5.0.2-dirty
	I (452) cpu_start: Min chip rev:     v0.0
	I (457) cpu_start: Max chip rev:     v3.99 
	I (461) cpu_start: Chip rev:         v1.0
	I (466) heap_init: Initializing. RAM available for dynamic allocation:
	I (473) heap_init: At 3FFAE6E0 len 00001920 (6 KiB): DRAM
	I (479) heap_init: At 3FFB6FC8 len 00029038 (164 KiB): DRAM
	I (486) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
	I (492) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
	I (498) heap_init: At 40094C98 len 0000B368 (44 KiB): IRAM
	I (506) spi_flash: detected chip: generic
	I (509) spi_flash: flash io: dio
	W (513) spi_flash: Detected size(4096k) larger than the size in the binary image header(2048k). Using the size in the binary image header.
	I (527) cpu_start: Starting scheduler on PRO CPU.
	I (0) cpu_start: Starting scheduler on APP CPU.
	I (637) example_connect: Start example_connect.
	I (647) wifi:wifi driver task: 3ffbed48, prio:23, stack:6656, core=0
	I (647) system_api: Base MAC address is not set
	I (647) system_api: read default base MAC address from EFUSE
	I (677) wifi:wifi firmware version: 57982fe
	I (677) wifi:wifi certification version: v7.0
	I (677) wifi:config NVS flash: enabled
	I (677) wifi:config nano formating: disabled
	I (687) wifi:Init data frame dynamic rx buffer num: 32
	I (687) wifi:Init management frame dynamic rx buffer num: 32
	I (697) wifi:Init management short buffer num: 32
	I (697) wifi:Init dynamic tx buffer num: 32
	I (697) wifi:Init static rx buffer size: 1600
	I (707) wifi:Init static rx buffer num: 10
	I (707) wifi:Init dynamic rx buffer num: 32
	I (717) wifi_init: rx ba win: 6
	I (717) wifi_init: tcpip mbox: 32
	I (717) wifi_init: udp mbox: 6
	I (727) wifi_init: tcp mbox: 6
	I (727) wifi_init: tcp tx win: 5744
	I (727) wifi_init: tcp rx win: 5744
	I (737) wifi_init: tcp mss: 1440
	I (737) wifi_init: WiFi IRAM OP enabled
	I (747) wifi_init: WiFi RX IRAM OP enabled
	I (747) phy_init: phy_version 4670,719f9f6,Feb 18 2021,17:07:07
	I (857) wifi:mode : sta (58:bf:25:8c:28:8c)
	I (857) wifi:enable tsf
	I (857) example_connect: Connecting to THEPOON...
	I (867) example_connect: Waiting for IP(s)
	I (3277) wifi:new:<1,0>, old:<1,0>, ap:<255,255>, sta:<1,0>, prof:1
	I (3947) wifi:state: init -> auth (b0)
	I (3947) wifi:state: auth -> assoc (0)
	I (3957) wifi:state: assoc -> run (10)
	I (3977) wifi:connected with THEPOON, aid = 2, channel 1, BW20, bssid = f2:79:e8:0d:6e:5d
	I (3977) wifi:security: WPA2-PSK, phy: bgn, rssi: -77
	I (3977) wifi:pm start, type: 1
	
	I (4037) wifi:AP's beacon interval = 102400 us, DTIM period = 2
	I (4987) esp_netif_handlers: example_netif_sta ip: 192.168.43.174, mask: 255.255.255.0, gw: 192.168.43.1
	I (4987) example_connect: Got IPv4 event: Interface "example_netif_sta" address: 192.168.43.174
	I (5637) example_connect: Got IPv6 event: Interface "example_netif_sta" address: fe80:0000:0000:0000:5abf:25ff:fe8c:288c, type: ESP_IP6_ADDR_IS_LINK_LOCAL
	I (5637) example_common: Connected to example_netif_sta
	I (5647) example_common: - IPv4 address: 192.168.43.174,
	I (5647) example_common: - IPv6 address: fe80:0000:0000:0000:5abf:25ff:fe8c:288c, type: ESP_IP6_ADDR_IS_LINK_LOCAL
	I (5667) example: Starting server on port: '80'
	I (5667) example: Registering URI handlers
	I (19317) example: Found header => Host: 192.168.43.174
	I (19327) example: Request headers lost
	I (19557) wifi:<ba-add>idx:0 (ifx:0, f2:79:e8:0d:6e:5d), tid:0, ssn:17, winSize:64


 
