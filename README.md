# mcwrap
Simple `macchanger` wrapper for randomising MAC addresses.

Ideal for those difficult to remember "predictable network interface names".

## Installation
```bash
#Dependencies
sudo apt install iproute2 gawk macchanger

#Download latest from github and set executable flag
curl https://raw.githubusercontent.com/xsoc/mcwrap/master/mcwrap -O
chmod +x ./mcwrap
```

## Usage
```bash
sudo ./mcwrap
```

### Example
```bash
sudo ./mcwrap
0 - wlan0
1 - eth0
Select interface (eg. 0): 0
Interface selected: wlan0
Current MAC:   00:00:00:00:00:00 (unknown)
Permanent MAC: 00:11:22:33:44:55 (unknown)
New MAC:       AA:BB:CC:DD:EE:FF (unknown)
```
