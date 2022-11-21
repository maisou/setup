# TH
```
[Misc] 
device_id = 0            # monitor id ถ้าคอมใช้หลายจอ แล้วเล่นเกมอยู่ที่จออื่นที่ไม่ใช่จอหลักให้ลองเปลี่ยนเป็นเลข 1 หรือ 2 แทน
Target_fps = 300         # ความเร็วในการแสกนหน้าจอเพื่อเช็คหาศัตรูที่อยู่บนหน้าจอ
Benchmark_mode = False   # เหมือนกับปุ่ม [HOME] ใช้สำหรับเช็คความเร็วในการคลิกเมาส์เมื่อเจอศัตรู

[Hotkey] 
pause_hotkey = 0x14     # ปุ่มสำหรับ pause โปรแกรม ค่าเดิมจะเป็นปุ่ม Capslock
                        # เมื่อกด จะหยุดการทำงานของ aimbot / triggerbot / flickbot กดอีกทีเพื่อเปิดใช้งาน
                        
[Cassidy]               # รวมทั้งโหมดตัวละครอื่นๆ
trigger_hotkey = 0x02   # ปุ่มใช้งาน triggerbot/flickbot ถ้าต้องการเปลี่ยนเป็นปุ่มอื่น ดูโค๊ดที่เว็บนี้ https://learn.microsoft.com/en-us/windows/win32/inputdev/virtual-key-codes
fov = 200               # field of view 
hitbox_scale = 0.70     # ค่าความกว้างของตัวละคร สำหรับ Triggerbot ค่าที่เหมาะสมจะอยู่ที่ประมาณ 0.6 - 0.8 กำลังพอดี
shoot_delay = 0.5       # ดีเลย์ในการยิงแต่ละนัด สำหรับทั้ง Triggerbot และ Flickbot
x_speed = 0.8           # ความเร็วในการขยับเมาส์แนวนอน (สำหรับ Flickbot)
y_speed = 0.5           # ความเร็วในการขยับเมาส์แนวตั้ง (สำหรับ Flickbot)
acceleration = 0.9      # ตัวเร่งความเร็วในการขยับเมาส์ทั้งแนวตั้งและแนวนอน ยิ่งเยอะ = ยิ่งเป้าดูดเข้าหาตัวศัตรู
flick_height = 6        # ความสูงในการ aim 0 = กลางลำตัว , 6 = ประมาณหัว

[Aimbot1]               # รวมทั้งโหมด aimbot อื่นๆ
aimbot_hotkey = 0x01    # ถ้าต้องการเปลี่ยนเป็นปุ่มอื่น ดูโค๊ดที่เว็บนี้ https://learn.microsoft.com/en-us/windows/win32/inputdev/virtual-key-codes
fov = 150               # field of view 
x_speed = 0.55          # ความเร็วในการขยับเมาส์แนวนอน
y_speed = 0.55          # ความเร็วในการขยับเมาส์แนวตั้ง
acceleration = 0.55     # ตัวเร่งความเร็วในการขยับเมาส์ทั้งแนวตั้งและแนวนอน ยิ่งเยอะ = ยิ่งเป้าดูดเข้าหาตัวศัตรู
free_y = False          # ปล่อยเมาส์ในแกนแนวตั้ง ถ้าตั้งเป็น True aimbot จะขยับเมาส์เฉพาะแนวนอน ทำให้ดูเนียนขึ้น
aim_height = 0          # ความสูงในการ aim 0 = กลางลำตัว , 6 = ประมาณหัว

[Precise]
Precise_mode = False    # สำหรับ Flickbot เพื่อเปลี่ยนวิธีการยิง ถ้าค่าเป็น True flickbot จะยิงเมื่อเป้าถึงตำแหน่ง X,Y ที่เจาะจงเท่านั้น เหมาะสำหรับถ้าต้องการยิงแต่หัวอย่างเดียว
                        # ถ้าเป็น False Flickbot จะยิงทุกส่วนของร่างกายศัตรูเมื่อเป้าอยู่ที่ศัตรู เหมือนกับ Triggerbot

Hitbox_size = 15        # Hitbox ของศัตรูเช็คจากตำแหน่ง X,Y  (สำหรับโหมด precise)
aim_height = 6          # ความสูงในการ aim 0 = กลางลำตัว , 6 = ประมาณหัว
```
# ENG
```
[Misc] 
device_id = 0            # monitor id if you playing overwatch on second monitor try change to 1 instead  
Target_fps = 300         # how fast program will try to read the screen shouldnt be too high or program will break 
Benchmark_mode = False   # Same as [HOME] button 

[Hotkey] 
pause_hotkey = 0x14     # pause cheat button default is capslock useful when trying to use ultimate 

[Cassidy]               # and other characters 
trigger_hotkey = 0x02   # change hotkey code see this https://learn.microsoft.com/en-us/windows/win32/inputdev/virtual-key-codes
fov = 200               # field of view 
hitbox_scale = 0.70     # between 0.65-0.8 is good  
shoot_delay = 0.5       # delay between each shot (both Triggerbot and Flickbot) 
x_speed = 0.8           # speed in X axis (while using Flickbot) 
y_speed = 0.5           # speed in Y axis 
acceleration = 0.9      # x and y multiplier  higher = faster 
flick_height = 6        # 0 = center of body , 6 = about the head 

[Aimbot1]               # and other aimbot modes
aimbot_hotkey = 0x01    # change hotkey code see this https://learn.microsoft.com/en-us/windows/win32/inputdev/virtual-key-codes  
fov = 150               # field of view 
x_speed = 0.55          # speed in X axis 
y_speed = 0.55          # speed in Y axis 
acceleration = 0.55     # x and y multiplier  higher = faster  
free_y = False          # aimbot will not move mouse in Y axis if True to look more legit 
aim_height = 0          # 0 = center of body , 6 = about the head 

[Precise]
Precise_mode = False    # True/False (change how Flickbot will work shoot only specific location if true or use Triggerbot hitbox if False) 
Hitbox_size = 15        # Hitbox around the aim position for precise mode only
aim_height = 6          # 0 = center of body , 6 = about the head 
```
