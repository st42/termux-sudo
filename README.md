# termux-sudo
A bash script that mimics sudo for Termux

Termux - a terminal emulator and Linux environment for Android

Download sudo and extract

Open Termux and change to extraction directory

Execute the following commands to install sudo:

cat sudo > /data/data/com.termux/files/usr/bin/sudo

chmod 700 /data/data/com.termux/files/usr/bin/sudo

Using cat to create sudo sets the correct ownership
