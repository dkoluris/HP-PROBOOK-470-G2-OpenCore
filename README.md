# HP-PROBOOK-470-G2-OpenCore
Successful attempt to install macOS on a 17" HP laptop

### Overall
So far the build is awesome, it's stable and robust, cold boot time to Mac in 23 seconds!

### Specifications

* Processor: Core i3-5010U 2.1GHz (Turbo Boost up to 3.2GHz)
* Graphics: Intel HD5500 (Up to 2GB of shared mem) / 900p 24bit
* RAM: 4GB DDR3 1600MHz
* Hard Disk: SATA 320GB HDD
* Wifi & Bluetooth: Intel Dual Band Wireless-AC 3160

### What is near 100% completed

* HD5500 2GB / Metal / DRM works on Chrome
* ALC??? Speakers / Headphones / Mic
* AC 3160 Wifi (limited bandwidth for now) / Bluetooth / AirDrop / Location Services
* Trackpad with Gestures support
* Proper mapping of available USB 2.0/3.0 ports
* RTL8111 Ethernet
* Internal HD Webcam
* SD Card reader
* Batt. indicator
* Balanced CPU PM Profile
* Sleep

### Bonus
* DRM content like Netflix, please use Chrome
* Use QuickESP to mount EFI partitions with ease, support me :)
* ICC Profile that improves the screen's native colors

### What doesn't work
* Trackpad tap works, but button click does not
* CMOS results in checksum error after reboot
* Apple TV DRM (Known issue for all iGPU Hackintosh)
