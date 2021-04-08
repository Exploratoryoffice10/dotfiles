<h1 align = 'center'> Linux </h1>
---


## To Change initial time on boot menu and the order of the fields


  - go to this folder `/etc/default` and open grub file.
    - here you can observe different fields. So by changing `GRUB_TIMEOUT` variable you can change the time grub waits before it jumps to the default action
    - you can select which should be default. so you can `GRUB_DEFAULT` value to any thing. In the previous menu the indexing starts from 0. So by changing it from zero to other value makes you to directly open other stuff
    - by setting `GRUB_TIMEOUT` = -1 your system waits till you manually select.

---
  
  - you can even change your background of your grub boot menu.
    - open `/usr/default/grub/themes/(os-name)`
    - edit the background.png file
    - and use the command ```bash update-grub ```
    - which saves these new settings
    
---
