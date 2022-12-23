# ENG
```
[Misc] 
device_id = 0            # monitor id if you playing overwatch on second monitor try change to 1 instead  
fps = 300                # how fast program will try to read the screen shouldnt be too high or program will break 
detection_level = 3      # how confident the cheat will detect the enemies 1-5 
                           some map like Dorado has many small purple paper pieces on the ground (first point)
                           bot get confused sometime and try to shoot that small pieces instead of enemy you trying to aim
                           so you may want to set detection_level to 4 or 5 to filter out that those papers
                           but trade off is that bot cant detect far away or small enemies
                           other maps you can set it to 1,2,3 depends how you like it
mouse_mode = 1           # there is 2 modes
                         # Mode 1 work with both Windows 10 and 11 but doesnt work with Valorant
                         # Mode 2 work with only Windows 10 and also Valorant (enemy purple)

[Hotkey] 
pause_hotkey = 0x14     # pause cheat button default is capslock useful when trying to use ultimate 

[Cassidy]               # and other characters 
trigger_hotkey = 0x02   # change hotkey code see this https://learn.microsoft.com/en-us/windows/win32/inputdev/virtual-key-codes
fov = 200               # field of view 
hitbox_scale = 0.70     # between 0.65-0.8 is good  
shoot_delay = 0         # delay between each shot (Triggerbot) Cassidy and Ashe should be 0
x_speed = 0.8           # speed in X axis (Flickbot) 
y_speed = 0.5           # speed in Y axis 
acceleration = 0.9      # x and y multiplier  higher = faster 
flick_height = 6        # 0 = center of body , 6 = about the head 

quick_scope = True      # For Widow only when True it will automatically turn off the scope after shot triggered to look more legit

[Aimbot1]               # and other aimbot modes
aimbot_hotkey = 0x01    # change hotkey code see this https://learn.microsoft.com/en-us/windows/win32/inputdev/virtual-key-codes  
fov = 150               # field of view 
x_speed = 0.55          # speed in X axis 
y_speed = 0.55          # speed in Y axis 
acceleration = 0.55     # x and y multiplier  higher = faster  
free_y = False          # aimbot will not move mouse in Y axis if True to look more legit 
aim_height = 0          # 0 = center of body , 6 = about the head 

[Precise]
Precise_mode = False    # True/False (change how Flickbot will work shoot only specific position if true or use Triggerbot hitbox if False) 
Hitbox_size = 15        # Hitbox around the aim position for precise mode only
aim_height = 6          # 0 = center of body , 6 = about the head 
```
