# Useful Commands
Just some commands and bits I find frequently helpful for working with Arch / Linux


## Pacman
#### Install package:
`pacman -Syu package_name package_name`

#### Search for package:
`pacman -Ss package_name`

#### List all explicitly installed packages:
`pacman -Qe`

#### Remove package and unneeded dependencies:
`pacman -Rs package_name`


## IWD
#### Start iwd.service:
`systemctl start iwd`

#### Start interactive iwd prompt:
`iwctl`

#### Find wireless device name:
`[iwd]# device list`

#### List available wireless networks:
`[iwd]# station device_name get-networks`

#### Connect to a wireless network:
`[iwd]# station device_name connect network_name`

#### Exit iwd interactive prompt:
`[iwd]# exit`


## Systemd
#### Show system status
`systemctl status`

#### Start a unit immediately:
`systemctl start unit_name`

#### Stop a unit immediately:
`systemctl stop unit_name`

#### Enable a unit to start automatically at boot:
`systemctl enable unit_name`

#### Disable a unit to no longer start at boot:
`systemctl disable unit_name`

