# Useful Commands
Just some useful and/or frequently helpful commands and bits for working with Arch / Linux

## Pacman
### Pacman install package
pacman -Syu package_name package_name

### Pacman search for package
pacman -Ss package_name

### List all explicitly installed packages
pacman -Qe

### Remove package and unneeded dependencies:
pacman -Rs package_name


## IWD
### Start iwd.service
systemctl start iwd

### Start interactive iwd prompt
iwctl

### Find wireless device name
[iwd]# device list

### List available wireless networks
[iwd]# station your_device get-networks

### Connect to a wireless network
[iwd]# station your_device connect your_network

### Exit iwd interactive prompt
[iwd]# exit
