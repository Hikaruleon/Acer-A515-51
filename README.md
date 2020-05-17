# Acer-A515-51 (No Discreet graphics version)
Opencore 5.8 build efi
Bios Version - Latest 2.1

i5 8250U, HD620, 1 USB 3, 2 USB 2, 1 USB C, 1 HDMI, 1 Gigabit ethernet, 30 pin display port, ELAN0501 pins 0x1b gpio, PS2 Keyboard, 1 x Sata, 1 x NVME(USE NVME kext and change appropriate config), 720p Webcam, Mic Array, 3.5mm Jack, 48WH battery.

Can't turn off bluetooth need to replaace WIFI+Bluetooth card (This laptop comes with QCA9377).

Idle intel power gadget 1.25W (CPU Package).

Only Download EFI hdmi other efi hdmi not working and will panic kernel, warning!!!, Deleted other EFI so it doesn't matter.

What is working? Almost all exept Wifi(Need to replace).


This is without wifi Patches.


Touchpad is working in Interrupt mode. After update need to build kext cache to work again(No wonder it won't work during installation, use usb mouse or in bios set to basic mode and use ps2touchpad kext from voodoops2).


Card reader is also working.


Battery, Brightness, Brightness keys, HEVC encode, QE/CI, Audio, Sleep, Hibernate, Keyboard mapped Alt to Cmd. All check.


Extras like Bootchime, Boot icons, NVRAM,  Windows/Linux dual boot, Setting startupdisk Osx drivers for Boot camp all working.
