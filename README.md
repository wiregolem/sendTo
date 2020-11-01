# sendTo
A bash script to send text messages to a kde-connect paired device

## Requirements
- Linux
- A terminal
- An Android device
- kdeconnect >= 1.3.3
  - kdeconnect is usually automatically installed with KDE Plasma
  - Debian: 
    - `$ sudo apt update` 
    - `$ sudo apt install kdeconnect`
  - Apt source: `http://deb.debian.org/debian buster/main amd64 Packages`
  - Depends on kde-cli-tools, plasma-framework, et al. (Runs on Kde Plasma desktop environment)
- The KDE Connect Android app
  - KDE Connect for Android is available on both Google Play and F-Droid.
  
## Device pairing
Pairing is quite intuitive, however you may follow [this guide](https://userbase.kde.org/KDEConnect#Pairing_two_devices_together)

## Setup
- Clone this repository 
  - `gh repo clone wiregolem/sendTo`
  - or
  - `git clone https://github.com/wiregolem/sendTo.git`
- Make executable
  - `$ chmod u+x`
- Add directory to PATH, optional
  - `export PATH=/your/directory/here:$PATH`
- If not added to PATH, user must specify directory to run, ie.
  - `./sendTo [number] [message]`
  
## Expected Usage
`sendTo 12025550111 "Hello, World"`

## Expected output 
NOTHING! If your device was paired successfully, check your phones text history! Message sent!


