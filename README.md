# rtl8723bu
Driver for Realtek RTL8723BU Wireless Adapter

# How to use?
## Get the source first.
Get it from Github repository with the following command in the Linux terminal.
```
git clone https://github.com/rpi3-rtl8723bu/rtl8723bu.git
cd rtl8723bu
```
Or get it as zip archive. Note: If you use the zip format, you will need to download the entire source EVERY time it is changed. By contrast,
a 'git pull' will get only the changed part. In addition, the git version will be able to access all branches, whereas the zip version only
handles one branch.
```
wget https://github.com/rpi3-rtl8723bu/rtl8723bu/archive/master.zip
unzip master.zip && rm master.zip
cd rtl8723bu-master
```
## Installation 
Then run the following commands in the Linux terminal.

```
make
sudo make install
sudo modprobe -v 8723bu
```
