# rtl8814AU
Realtek 8814AU USB WiFi driver

Forked off of tprichers fork, which works for newer kernels (tested on 4.13.x)

Added DKMS support

From your src dir

````
sudo cp -R . /usr/src/rtl8814au-4.3.21
sudo dkms build -m rtl8814au -v 4.3.21
sudo dkms install -m rtl8814au -v 4.3.21
````

This should keep your TPLink adapter working post kernel updates.
