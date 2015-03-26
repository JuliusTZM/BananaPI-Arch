BananaPi Arch
================
![](http://www.igorpecovnik.com/wp-content/uploads/2014/09/bananapi-ssh.png)

Script to create bootable SD card image of Arch for Banana PI.

[Check build libraries](https://github.com/igorpecovnik/lib)

Prebuild images, support & history of Igor's development
------------------
[http://www.igorpecovnik.com/2014/09/07/banana-pi-debian-sd-image/](http://www.igorpecovnik.com/2014/09/07/banana-pi-debian-sd-image/ "Download")

Thank you for your donation of Igor
------------------

[![Paypal donate](https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CUYH2KR36YB7W)

![His bitcoin address](http://www.igorpecovnik.com/wp-content/uploads/2014/10/bitcoinigor.png)

17vT6hV83EQ6rizbWeasfy1tWEzFpzYqEE

DIY
------------------
- [Install Arch] into your (virtual) PC
- Login as root and execute:
```shell
sudo pacman -S git
cd ~
git clone https://github.com/JuliusTZM/BananaPI-Arch
chmod +x ./BananaPI-Arch/build.sh
cd ./BananaPI-Arch
```
edit build.sh and alter configuration

```shell
sudo ./build.sh
```
- Wait around 3h on a 10Mbit line and average desktop computer.
- If build is succesfull you will find zipped image in your **output/output** directory. Unzip and burn with supplied writter or DD (Unix / Mac) to your SD card.
- Boot your Banana :=)
