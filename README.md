# android
android playground

# zsh completition

To disable completion on the adb comnand:

    compdef -d adb

SDK path:

    ~/Library/Android/sdk/platform-tools

List devices:

    ./adb devices -l

Boot in recovery mode:

    adb reboot recovery

Load ROM:

    adb sideload ~/Downloads/rom

Fastboot continue to boot device:

    fasbtoot continue

Root device (KingRoot):

    http://www.kingroot.net/

Rom Manager (ClockworkMod) to install recovery images:

    https://play.google.com/store/apps/details?id=com.koushikdutta.rommanager

Developer options / mode:

    1. click 7 times on settings / About <device> / Build number
    2. Enable developer options
    3. Enable USB debugging
