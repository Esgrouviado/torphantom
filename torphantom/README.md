# TorPhantom
## Version 1.0 By J 
A fork of [TorGhost](https://github.com/susmithHCK/torghost), a little utilitly used to route all traffic through TOR.
Updated to Python3

Currently depends on macchanger and tor.
must systemctl enable tor.service

This script spoofs your mac address, and then routes all traffic through the TOR network. It is currently a WIP.


If you are aware of another solution to this problem please submit a pull request!

**TorPhantom is a tool,inslaled by you, and users are responsible for any risks or activities performed while using it.**


1. More Linux support (currently install script is for Debian based distros only)
2. Python 3 updated

## Linux:

#### Debian/Ubuntu:

```sh
chmod +x install.sh
./install.sh
```

#### Arch:

```sh
chmod +x install-pac.sh
./install-pac.sh
```



# TorPhantom

## Overview
TorPhantom is a utility that routes all network traffic through the TOR network and spoofs your MAC address for enhanced privacy. It is a Python 3 fork of [TorGhost](https://github.com/susmithHCK/torghost).

**Status:** BETA – Use at your own risk. You are responsible for any activities performed while using TorPhantom.

## Features
- Routes all traffic through TOR
- Spoofs MAC address using macchanger
- Supports multiple Linux distributions

## Dependencies
- Python 3
- macchanger
- tor

**Note:** You must enable the tor service:
```sh
sudo systemctl enable tor.service
sudo systemctl start tor.service
```

## Installation

### Debian/Ubuntu
```sh
chmod +x install.sh
./install.sh
```

### Arch
```sh
chmod +x install-pac.sh
./install-pac.sh
```

### RHEL/CentOS/Fedora
```sh
chmod +x install-rpm.sh
./install-rpm.sh
```

## Usage

```sh
  _______         _____  _                 _                  
 |__   __|       |  __ \| |               | |                 
        | | ___  _ __| |__) | |__   __ _ _ __ | |_ ___  _ __ ___  
        | |/ _ \| '__|  ___/| '_ \ / _` | '_ \| __/ _ \| '_ ` _ \
        | | (_) | |  | |    | | | | (_| | | | | || (_) | | | | | |
        |_|\___/|_|  |_|    |_| |_|\__,_|_| |_|\__\___/|_| |_| |_|
        v1.0 By J 

USAGE:
        torphantom start                # Start TorPhantom
        torphantom start -i <interface> # Start with MAC address spoofing
        torphantom stop                 # Stop TorPhantom
```

## Roadmap
- More Linux support (currently install script is for Debian-based distros only)
- Python 3 updates

## Disclaimer
TorPhantom is in BETA. You are solely responsible for any risks or activities performed while using this tool, regardless of its development status.

## Contributing
If you know of another solution or want to improve TorPhantom, please submit a pull request!

## Support
For issues or suggestions, open an issue or submit a pull request on GitHub.

