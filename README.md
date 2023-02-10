# SIVA GRUB theme

##### Installation

Copy the "siva" folder with root privileges to /boot/grub/themes/

Edit /etc/default/grub and add:
```
GRUB_THEME=/boot/grub/themes/siva/theme.txt
```
Update grub (for everybody else) :
```
sudo update-grub
```
Update grub (For arch users btw) :
```
sudo grub-mkconfig -o /boot/grub/grub.cfg
```


