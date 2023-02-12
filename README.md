# SIVA GRUB theme (Green)

##### Preview

![20230205_092405](https://user-images.githubusercontent.com/43517199/217972292-4d7aa9db-c864-4cbf-8ad7-6fe8ad9ffb82.jpg)

# SIVA GRUB theme (Red)

##### Preview



##### Installation

Copy the "siva" folder with root privileges to /boot/grub/themes/

Edit /etc/default/grub and add:    (For Green Theme)
```
GRUB_THEME=/boot/grub/themes/sivagreen/theme.txt
```
Edit /etc/default/grub and add:    (For Red Theme)
```
GRUB_THEME=/boot/grub/themes/sivared/theme.txt
```
Update grub (for everybody else) :
```
sudo update-grub
```
Update grub (For arch users btw) :
```
sudo grub-mkconfig -o /boot/grub/grub.cfg
```


