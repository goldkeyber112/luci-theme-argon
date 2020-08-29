# luci-theme-argon

A new Luci theme for OpenWRT  
Argon is a clean HTML5 theme for LuCI. It is based on luci-theme-material and Argon Template  


## Notice

📌This branch only matches lean openwrt (luci 18.06).


## How to build

Enter in your openwrt/package/lean
```
cd lede/package/lean  
rm -rf luci-theme-argon  
git clone -b 18.06 https://github.com/goldkeyber112/luci-theme-argon.git  
make menuconfig #choose LUCI->Theme->Luci-theme-argon  
make -j1 V=s  
```

## Install 
```
wget --no-check-certificate https://github.com/goldkeyber112/luci-theme-argon/releases/download/1.5.1/luci-theme-argon-1.5.1_1.5.1-01-20200622_all.ipk
opkg install luci-theme-argon-1.5.1_1.5.1-01-20200622_all.ipk
```
## Screenshots

### Light  
<img src="https://github.com/goldkeyber112/luci-theme-argon/raw/18.06/screenshots/mobile-iPhone%20X.png" width="50%">


### Dark  
<img src="https://github.com/goldkeyber112/luci-theme-argon/raw/18.06/screenshots/mobile_dark-iPhone%20X.png" width="50%">


## Thanks to 
This project is based on jerrykuku's source code,modified to self-use. For who use luci 19.07 and more support, please visit the original project.  
the original project &#xA0;[luci-theme-argon](https://github.com/jerrykuku/luci-theme-argon) &#xA0;👈👍👍👍
