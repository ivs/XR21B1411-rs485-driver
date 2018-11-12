# XR21B1411-rs485-driver
XR21B1411 with forced rs485 mode

Inpired by this project: https://github.com/Goshik92/XR21B1411-RS-485-driver

Same patch but for 3.6+ kernels based on original Exar driver code: https://www.exar.com/content/document.ashx?id=21651

Successfully tested on BeagleBone Black Debian with 4.14.71-ti-r80 kernel

To build install linux headers for your kernel:
```
apt-get install linux-headers-$(uname -r)
```
And follow instructions from original Readme.txt

You will see `/dev/ttyXRUSB0` device file