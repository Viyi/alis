## My WIP Custom Arch Installer

Forked from https://github.com/picodotdev/alis

### Running

Load keyboard keymap, eg. loadkeys es, loadkeys us, loadkeys de
```
loadkeys -d
```
Connect to WIFI network. _ip link show_ to know WIFI_INTERFACE (Optional) 
```
iwctl --passphrase "[WIFI_KEY]" station [WIFI_INTERFACE] connect "[WIFI_ESSID]"        
```
Download install Script
```
curl https://raw.githubusercontent.com/picodotdev/alis/master/download.sh | bash -s -- -u Viyi
```
Start asciinema video recording (Optional) 
```
./alis-asciinema.sh     
```
Install
```
./alis.sh              
```
