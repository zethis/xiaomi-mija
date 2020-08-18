# xiaomi-mija
get info from this little beauty: https://bit.ly/3h852qF

# Please install bluez package before
https://packages.ubuntu.com/focal/bluez

# How to use
./xiaomi_temp.sh $(room_name) $(mija_mac_addr)

Example:
--------
```bash
./xiaomi_temp.sh test A4:C1:38:EC:94:0C
Valid MAC
Device name =  test
Device MACaddr =  A4:C1:38:EC:94:0C
Notification handle = 0x0036 value: a3 0b 39 c6 0b
./xiaomi_temp.sh: line 71: warning: command substitution: ignored null byte in input
firmware= 1.0.0_0106
./xiaomi_temp.sh: line 80: warning: command substitution: ignored null byte in input
name= LYWSD03MMC
Reading Mijia...
Hardware: {Firmware Version:1.0.0_0106 / Hardware Revision:B1.4 / BT Name:LYWSD03MMC / Battery Level:99}
Sensors:{Temperature:29.79 / Humidity:57 / Voltage:3.014}
```
