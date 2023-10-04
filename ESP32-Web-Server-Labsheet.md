# การทดลอง Webserver อย่างง่ายด้วย ESP32

##  ขั้นตอนการทดลอง 
### 1. สร้าง Project ใหม่ ชื่อ ESP32-Web-Server


![Alt text](./Pictures/1.Create-new-project.png)

1.1 ใช้ template simple server

![Alt text](./Pictures/2.Select-project-template.png)


###  2. Build โปรเจค 1 ครั้ง 
เพื่อให้ระบบสร้างไฟล์ sdkconfig เราจะเข้าไปแก้ WiFI ssid และ password
 
![Alt text](./Pictures/3.Edit-SSID-snd-Password.png)

###  3. รันโปรแกรม แก้ไขที่ผิด (ถ้ามี)

![Alt text](./Pictures/4.Found-Error.png)

พบ error เนื่องจากค่าเริ่มต้นของโปรแกรมกำหนดให้ความยาวของ HTTP request header มีต่าสูงสุด 152 ตัวอักษร เราต้องแก้ให้เป็น 1024 

###  4. แก้ไข Max HTTP Request Header Lenght เป็น 1024

![Alt text](./Pictures/5.Change-Req-Header-Len.png)

###  5. รันโปรแกรม แก้ไขที่ผิด (ถ้ามี)


ตัวอย่างผลการทำงาน (เมื่อดูจาก browser)
![Alt text](./Pictures/6.Sample-Result.png)


###  6. บันทึกผลการทดลอง ทั้งที่หน้าจอ monitor ของ ESP32 และหน้า Web browser

![ภาพ](https://github.com/kammam19/ESP32-Web-Server/assets/112167732/2a6c9a14-38ac-40e5-b05d-3c2c64ecbb9b)

![ภาพ](https://github.com/kammam19/ESP32-Web-Server/assets/112167732/f4e59a87-9271-4555-aed7-2231d36c7b52)


###  7. ส่งงาน
pull request พร้อมแนบ link ไปยัง repository ของโปรเจคด้วยนะ

https://github.com/kammam19/ESP32-Web-Server
