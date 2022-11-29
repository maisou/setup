# TH
```
[F2] = Widowmaker [F3] = Cassidy [F4] = Ashe [F5] = Sojourn 
[F6] = Aimbot #1 [F7] = Aimbot #2 [F8] = Aimbot #3 [F9] = Aimbot #4 
[F10] = รีโหลด Config
[F12] = เปิด/ปิด ใช้งาน Flick Mode
[HOME] เทสความเร็วในการยิงเมื่อเจอศัตรู
[INSERT] โปรมองทะลุ
[ALT+1] เปิดโหมดซ่อน Ui 
        ต้องตั้งค่าในเกมตามนี้ก่อน Controls -> Interface -> Toggle UI -> Mouse Wheel Scroll up
[END] ปิดโปรแกรม

** ปรับเกมเป็นโหมด borderless windowed และปรับสีศัตรูให้เป็น Magenta **

เมื่อเปิดโปรแกรมทุกครั้งจะโหลดตั้งค่าเริ่มต้นของตัวละคร Cassidy (โหมด Triggerbot) สามารถเปลี่ยนเป็นโหมดอื่นโดยการกด (F2 F3 F4 ... F12 อื่นๆ)

วิธีการเปลี่ยนตั้งค่าต่างๆ ให้เปิด profiles.ini ด้วย notepad เมื่อแก้ค่าเสร็จกดเซฟไฟล์ (Ctrl + S) จากนั้นกด F10 โปรจะทำการโหลดค่าต่างๆใหม่โดยไม่ต้องปิดเปิดโปรใหม่

ถ้าต้องการแก้ปุ่ม Hotkey สำหรับใช้งานโปรในโหมดต่างๆ ให้ดูโค๊ดจากเว็บนี้ https://learn.microsoft.com/en-us/windows/win32/inputdev/virtual-key-codes  เช่น 0xA4 = ปุ่ม Alt

Widow/Cassidy/Ashe/Sojourn จะมี Triggerbot กับ Flickbot สำหรับ Sojourn จะเป็นท่ายิงคลิกขวา Railgun

ในขณะที่กำลังใช้งานตัวละครที่มี Triggerbot เมื่อกด F12 จะเปลี่ยนเป็น Flick Mode กดอีกทีเพื่อกลับไปเป็น Triggerbot

Aimbot สามารถตั้งค่าได้ 4 โปรไฟล์ ใช้สำหรับตั้งค่าพวกตัวละคร Tracer/76/Dva/Zarya และอื่นๆ

Precise Mode เป็นฟังชั่นสำหรับ Flickbot เมื่อเปิดใช้งานโปรจะทำงานโดยการ aim ไปที่จุด X,Y บนร่างกายแบบเจาะจง เหมาะสำหรับคนที่อยากให้ยิงหัวอย่างเดียว 
แต่เนื่องจากโปรนี้ไม่ได้ยุ่งกับตัวเกมเช่นการ inject ไปในตัวเกมเพื่อดึงค่า Head offset ออกมาทำให้การค่า X,Y ที่ได้มาอาจคลาดเคลื่อนบ้าง 

กดปุ่ม Insert เพื่อเปิดโปรมองทะลุ บางเกมจะแสดงผลผิดฝั่ง (ขึ้นกรอบฝั่งตัวเอง) ให้กดปุ่ม PageUP บนคีย์บอร์ดเพื่อเปลี่ยนเป็นแสดงผลฝั่งศัตรู

โหมดซ่อน UI ใช้สำหรับตัวละครที่ต้องใช้ความแม่นยำสูง เพื่อให้โปรไม่พยายามยิงไปที่เลือด/ชื่อของศัตรู 
เมื่อเปิดใช้งานโหมดนี้ เวลากด hotkey ค้าง aimbot/flickbot/triggerbot จะทำการซ่อนเลือด/ชื่อ เพื่อเพิ่มความแม่นยำ
ในเกมต้องไปตั้งที่ Options  Controls -> Interface -> Toggle UI -> Mouse Wheel Scroll up


```


# ENG
```

[F2] Widowmaker [F3] Cassidy [F4] Ashe [F5] Sojourn
[F6] Aimbot #1 [F7] Aimbot #2 [F8] Aimbot #3 [F9] Aimbot #4

[F10] Reload Config
[F12] Enable/Disable Flickbot
[HOME] to benchmark reaction speed of bot from rendering to mouse trigger
[INSERT] ESP/Wallhack
[ALT+1] Enable/Disable Hide UI mode
        Game Options Controls -> Interface -> Toggle UI -> Mouse Wheel Scroll up

[END] to exit program

** change Overwatch to Borderless Windowed mode and enemy color to Magenta  **

Everytime you launch the cheat it will load Cassidy mode (Triggerbot) by default then you can switch to other mode using (F2 F3 ... F12 etc.)

To update character settings. Open 'profiles.ini' using notepad edit the value then save file (Ctrl + S) and 
press [F10] to force cheat to reload config without restart program 

If you want to change the hotkey code see this > https://learn.microsoft.com/en-us/windows/win32/inputdev/virtual-key-codes 

Only Widow/Cassidy/Ashe/Sojourn has Triggerbot and Flickbot  (for sojourn is railgun beam)

While using Triggerbot you can press F12 to turn on/off Flickmode this will not conflict with Aimbot mode

Aimbot has 4 Profiles you can setting up them for Tracer/76/Dva/Zarya etc.

Precise Mode is for Flickbot only it will specific move mouse at exact X and Y position (For Head/Body etc) 
since this is external colorbot there is no way to get exact Head offset from the game 
and this is very close to that if you want to try to only shoot the head.

Flickbot without Precise mode will use same hitbox as Triggerbot more consistant shots but will try to shoot any part of the body

The [HOME] button is for benchmarking the reaction speed from enemy detection to mouse click (Triggerbot only) and should be less than 15ms

[INSERT] to enable ESP/Wallhack sometimes it bugged showing boxes on your teammates press [PageUp] on your keyboard to fix this

Hide UI is for characters that require high precision. so the bot doesn't try to shoot at the enemy's health bar/name.
When this mode is enabled, while holding down the hotkey (aimbot/flickbot/triggerbot) will hide the health bar/name to increase accuracy
Need to change In-Game Hotkey for Toggle UI to Mouse Wheel Scroll "UP" first 
Game Options Controls -> Interface -> Toggle UI -> Mouse Wheel Scroll UP

```
