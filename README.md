# Install Mouse Drivers

### ปิดใช้งาน Secure Boot / Memory integrity

![](https://blog.janjan.net/wp/wp-content/uploads/2022/10/asrock-uefi-secure-boot-enabled-02.jpg)
> เข้าหน้าต่าง BIOS แล้วเลื่อนหาหัวข้อ Secure Boot แล้วเลือก Disable

![](https://i.imgur.com/lzJ7aCT.png)
> กดปุ่ม Window แล้ว search หา Core Isolation

#### ให้ทำตามทุกขั้นตอน
#### ถ้ามีปัญหา error ยังไงให้แคปรูปมาให้ดูได้
#### วิธีติดตั้งไดร์เวอร์เมาส์ (จำเป็นต้องติดตั้ง)

1.  แตกไฟล์ driver.zip แล้วเปิด folder เข้าไป
2.  เปิด powershell ด้วย admin (คลิกขวาที่ปุ่มวินโดว์)
3.  ก็อปที่อยู่โฟลเดอร์ driver ตามรูป
4.  พิมพ์ cd ตามด้วยที่อยู่โฟลเดอร์ driver ที่ก็อปมาตามข้อ 3. แล้ว Enter
5.  คำสั่งแรกพิมพ์  ```./dc64.exe install dd.mou.94396.inf "dd.mou.94396"```      แล้ว Enter 
6.  คำสั่งสองพิมพ์  ```./64.exe install DDHID1906.inf "DDHID1906\HID_DEVICE"```   แล้ว Enter

พอขึ้นว่า ```Drivers installed Successfully```  ทั้ง 2 บรรทัดให้ปิดหน้าต่าง powershell ไป

![](https://i.imgur.com/nKLVp0B.png)
![](https://i.imgur.com/waYp3hS.png)

# Bot install

1. แตกไฟล์ bot.zip 
2. เอาไฟล์ mdrv.dll ไปวางไว้ที่ไดฟ์  C:/  ตามรูป
3. เปิด main.exe แล้วกรอกโค๊ดเปิดใช้งานโปรแกรม

![](https://i.imgur.com/zDkTUim.png)

# In-Game settings

### (Color Blindness) <br />
Enemy UI Color  =  Magenta

### (Video) <br />
Display Mode = Borderless Windowed <br />
Frame rate = Custom <br />
Maximum Frame Rate = 600

### (Graphics Quality) <br />
Low ทุกอย่างตามรูป

Gamma/Contrast/Brightness = Default

![](https://i.imgur.com/INbk0xj.png)
![](https://i.imgur.com/zkeczgN.png)
![](https://i.imgur.com/BC0bRWu.png)

# Unlock high FPS

ปิด G-Sync / FreeSync Unlock FPS ให้สูงที่สุด

![](https://i.imgur.com/OsqeQf1.png)

