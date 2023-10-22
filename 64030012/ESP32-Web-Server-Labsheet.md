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
![image](https://github.com/Fixckpx/ESP32-Web-Server/assets/115066186/4cf8ca88-31f7-4bd5-bad3-588a629a6048)
![Screenshot 2023-10-22 154410](https://github.com/Fixckpx/ESP32-Web-Server/assets/115066186/efbe893c-565c-42be-af0c-66c89bd397f8)
![Screenshot 2023-10-22 154405](https://github.com/Fixckpx/ESP32-Web-Server/assets/115066186/2d97c02a-412e-4435-b31a-43d8b2abf81d)
![Screenshot 2023-10-22 154357](https://github.com/Fixckpx/ESP32-Web-Server/assets/115066186/01a772e4-f49e-4860-8e9a-f6d94c13b23c)
![Screenshot 2023-10-22 154345](https://github.com/Fixckpx/ESP32-Web-Server/assets/115066186/fcec3775-9a47-4bad-b8a8-cd161efcfda3)
![Screenshot 2023-10-22 154336](https://github.com/Fixckpx/ESP32-Web-Server/assets/115066186/41cee831-032e-4a8d-bbc4-7842714d8ef0)
![Screenshot 2023-10-22 154326](https://github.com/Fixckpx/ESP32-Web-Server/assets/115066186/84ecde8a-e7b1-436b-9261-bd5a69abc2c7)
![Screenshot 2023-10-22 154314](https://github.com/Fixckpx/ESP32-Web-Server/assets/115066186/f8eaaabf-b29f-4406-8dcd-7d6ac0af5657)

###  7. ส่งงาน
pull request พร้อมแนบ link ไปยัง repository ของโปรเจคด้วยนะ

https://github.com/Fixckpx/ESP32-Web-Server
