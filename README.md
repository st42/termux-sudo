# termux-sudo
A bash script that mimics sudo for Termux

Termux is a terminal emulator and Linux environment for Android

Installing sudo:

1. Download sudo and extract
2. Open Termux and change to extraction directory
3. Execute the following commands
```
cat sudo > /data/data/com.termux/files/usr/bin/sudo
chmod 700 /data/data/com.termux/files/usr/bin/sudo
```
Using cat to create sudo sets the correct file ownership
