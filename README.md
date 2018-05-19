# rtl8812AU_8821AU_linux

## Quick User Guide

```bash
# first clone repository
# run install shell
./install.sh

# SoftAP mode
ifconfig wlan0 down
ifconfig wlan0 192.168.0.1 netmask 255.255.255.0
ifconfig wlan0 up
./wpa_supplicant_hostapd/hostapd ./wpa_supplicant_hostapd/rtl_hostapd_5G.conf -B

# you may also ned dhcpd
systemctl start dhcpd
```



### 

