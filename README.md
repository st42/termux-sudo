# termux-sudo
A bash script that provides sudo for Termux  
Termux is a terminal emulator and Linux environment for Android

**Requirements**

Rooted phone with su binary  
SUDO WILL NOT WORK WITHOUT SU!

**Installing sudo**

1. Download sudo and extract
2. Open Termux and change to extraction directory
3. Execute the following commands to place sudo into the correct directory with the proper permissions and ownership
```
cat sudo > /data/data/com.termux/files/usr/bin/sudo
chmod 700 /data/data/com.termux/files/usr/bin/sudo
```

**Features**

- Sets up its environment automatically on first run, no need to do anything but use it
- Can be used like ordinary sudo (but only as root, no other user)
- Runs commands in current directory
- Generates output in shell currently using
- Can be used in other bash scripts
- Can run built in Termux binaries and exteral binaries
```
Usage:

sudo su [-]  
  Drop to root shell

sudo <command> [<args>]  
  Run command as root with optional arguments
```

**This was inspired by the following:**

https://github.com/cswl/tsu  
https://gist.github.com/cswl/cd13971e644dc5ced7b2  
