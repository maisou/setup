# Install Mouse Drivers

### ปิดใช้งาน Secure Boot / Memory integrity

![](https://blog.janjan.net/wp/wp-content/uploads/2022/10/asrock-uefi-secure-boot-enabled-02.jpg)
> เข้าหน้าต่าง BIOS เลื่อนหาหัวข้อ Secure Boot แล้วเลือก Disable

![](https://media.discordapp.net/attachments/1033371424972349440/1033395675657932870/unknown.png)
> กดปุ่ม Window แล้ว search หา Core Isolation ปรับเป็น Off ที่ Memory integrity

##### พยายามอย่าข้ามขั้นตอน ถ้ามีปัญหา error ยังไงให้แคปรูปมาให้ดูได้
##### วิธีติดตั้งไดร์เวอร์เมาส์ (จำเป็นต้องติดตั้ง ดูรูปภาพประกอบด้านล่าง)


1. แตกไฟล์ bot-win11.zip บน Desktop เปิดโฟลเดอร์เข้าไปแล้วก๊อปที่อยู่โฟลเดอร์ไว้
2. เปิด powershell ด้วย admin  (คลิกขวาที่ปุ่ม windows เลือก Terminal (admin) )
3. พิมพ์ cd แล้วตามด้วยโฟลเดอร์ที่ก๊อปมา แล้วกด Enter
4. พิมพ์  ```.\install-driver.exe /install```   เพื่อติดตั้ง driver พอขึ้น success ให้รีคอมทีนึง

5. หลังรีคอมเสร็จ เอา 3 ไฟล์นี้ ไปวางไว้ที่ C:/
```
mdrv2.dll
interception.dll
InputInterceptor.dll
```
6. เปิด main.exe แล้วกรอกโค๊ดเปิดใช้งานโปรแกรม

![](https://media.discordapp.net/attachments/1033371424972349440/1033396183080636477/unknown.png)

![](https://images2.imgbox.com/80/e2/HPVUlfEH_o.png)

![](https://media.discordapp.net/attachments/1033371424972349440/1033397082653995159/unknown.png)

![](https://media.discordapp.net/attachments/1033371424972349440/1033397640253145148/unknown.png)

![](https://media.discordapp.net/attachments/1033371424972349440/1033398253267456192/unknown.png)

![](https://media.discordapp.net/attachments/1033371424972349440/1033398532129959987/unknown.png)


# In-Game settings

### (Color Blindness) <br />
Enemy UI Color  =  Magenta

### (Video) <br />
Display Mode = Borderless Windowed <br />
Frame rate = Custom <br />
Maximum Frame Rate = 600 <br />
V-Sync = Off

### (Graphics Quality) <br />
Low ทุกอย่างตามรูป

Gamma/Contrast/Brightness = Default

![](https://i.imgur.com/INbk0xj.png)
![](https://i.imgur.com/zkeczgN.png)
![](https://i.imgur.com/BC0bRWu.png)

# Unlock high FPS

ปิด G-Sync / FreeSync / V-Sync Unlock FPS ให้สูงที่สุด

![](https://i.imgur.com/OsqeQf1.png)

