### Install dump1090-mutability on Debian13 Trixie and RPiOS Trixie
**The dump1090+mutability is no more available in Debian 13 trixie repositories.**</br>

**Workaround to install dump1090-mutability**</br>

The dump1090-mutability packages are available from Debian Package Archive for "Bookworm". These install and work OK on "Trixie" as well.</br>

To download & install dump1090-mutability packages from Debian Package Archives for Bookworm, use following commands:

### (1) RPi with 32-bit OS (armhf)
```
sudo apt install lighttpd

wget  http://http.us.debian.org/debian/pool/main/d/dump1090-mutability/dump1090-mutability_1.15~20180310.4a16df3+dfsg-8.1_armhf.deb  

sudo dpkg -i dump1090-mutability_1.15~20180310.4a16df3+dfsg-8.1_armhf.deb  

sudo apt --fix-broken install 

sudo usermod -aG plugdev dump1090  

sudo reboot

```
</br>

### (2) RPi with 64-bit OS (arm64 / aarch64) 
```
sudo apt install lighttpd  

wget  http://http.us.debian.org/debian/pool/main/d/dump1090-mutability/dump1090-mutability_1.15~20180310.4a16df3+dfsg-8.1_arm64.deb  

sudo dpkg -i dump1090-mutability/dump1090-mutability_1.15~20180310.4a16df3+dfsg-8.1_arm64.deb  

sudo apt --fix-broken install  

sudo usermod -aG plugdev dump1090  

sudo reboot

```

### (3) PC / Laptop (amd64) 
```
sudo apt install lighttpd  

wget  http://http.us.debian.org/debian/pool/main/d/dump1090-mutability/dump1090-mutability_1.15~20180310.4a16df3+dfsg-8.1_amd64.deb  

sudo dpkg -i dump1090-mutability_1.15~20180310.4a16df3+dfsg-8.1_amd64.deb  

sudo apt --fix-broken install  

sudo usermod -aG plugdev dump1090  

sudo reboot

```

### (4) PC/Laptop (i386)
```
sudo apt install lighttpd  

wget  http://http.us.debian.org/debian/pool/main/d/dump1090-mutability/dump1090-mutability_1.15~20180310.4a16df3+dfsg-8.1_i386.deb  

sudo dpkg -i dump1090-mutability_1.15~20180310.4a16df3+dfsg-8.1_i386.deb  

sudo apt --fix-broken install  

sudo usermod -aG plugdev dump1090  

sudo reboot

```

</br>

