# mardis
Great marshal python2 decompiler++
# what's new?
The latest version supports decompilation in memory, no longer involving system commands. and added `multiexec` decompilation, because previously the tool would stop when it got more than 1 `exec` words.
# quick install
here I run this tool using the Termux system. If the system you use is different, the installation may be different. but what is needed remains the same.
needs
- python2.7
- py-module: uncompyle6==3.7.4
- py-module: xdis==5.0.11

# COMMANDS:⬇️
```
termux-setup-storage
pkg update
pkg upgrade
pkg install git python2
python2 -m pip install --upgrade pip
python2 -m pip install xdis==5.0.11
python2 -m pip install uncompyle6==3.7.4
git clone https://github.com/DARK-NET-604/Mardis
cd Mardis
dpkg -i mardis_1.0_all.deb
```
# now you can run with the command:⬇️
````
python2 setup.py
````
# Usage:⬇️
mardis [filename|output]

filename = the file you want to decompile
output = For files that store decompilation results, the default is `code.py`

# Find Me on :

[![Facebook](https://img.shields.io/badge/Facebook-green?style=for-the-badge&logo=facebook)](https://www.facebook.com/DARK.NET.604?mibextid=ZbWKwL)
[![Teligram](https://img.shields.io/badge/Chat-Teligram-blue?style=for-the-badge&logo=teligram)](https://t.me/DARK_NET_604)
[![Messenger](https://img.shields.io/badge/Chat-Messenger-blue?style=for-the-badge&logo=messenger)](https://m.me/DARK.NET.604)
[![Github](https://img.shields.io/badge/Github-Github-143green?style=for-the-badge&logo=github)](https://github.com/DARK-NET-604)


# Enjoy All
# Thanks ❣️❣️
