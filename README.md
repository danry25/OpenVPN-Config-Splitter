# OpenVPN Config Splitter
Network Manager's OpenVPN Import feature doesn't accept an inline configuration file. Which is
really annoying, because inline configurations are the easiest to distribute. This script will parse
an inline config, move all the bits into a folder and generate an importable config. I've only
tested it with the files generated by the pfSense OpenVPN Client Export Utility, but it should
pretty much work on any valid OpenVPN file.

## todo
* Automatically import into Network Manager, maybe using [this](https://unix.stackexchange.com/a/237886) method
* A proper configuration file
* Maybe some automatic self-extracting magic so it can all be sent as one file. "Run this script to get on the VPN"
