# # OpenCore_Intel_Skylake_EFI
OpenCore 0.7.8 Intel Skylake EFI  
macOS Big Sur 11.2  
macOS Big Sur 11.2.1  
macOS Big Sur 11.6.3  
macOS Monterey 12.2.1  
http://www.neko.ne.jp/~freewing/software/osx86_hackintosh_big_sur_create_usb_install_media_opencore/  

## # 2021/02/20 Intel Skylake
Intel Skylake  
Core i3-6100U, Intel HD Graphics 520  

## # works fine  
* USB
* HDMI Display
* LAN Network
* WiFi and Bluetooth
* SD-Card Reader
* Built-in Camera

## # not work   
* HDMI Display Audio
* Core i3-6100U, Intel HD Graphics 520 graphics acceleration on Monterey (Black Screen)  
 Have to change boot-args '-_igfxvesa' to '-igfxvesa'

## # This EFI set works following System  
* HYSTOU FMP03 Intel Skylake Core i3-6100U  
http://www.neko.ne.jp/~freewing/hardware/hystou_barebone_fmp03_i3_6100u/  
