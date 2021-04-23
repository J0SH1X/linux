# Information

Mainline 5.12 kernel with support for LG G8s added


# What works

`Boot'
`Framebuffer device taken over from bootloader`
`vol up vol down and power keys`
`gpio`
`wifi`
`adsp slpi modem subprocessors are booted up`
`charging , its slow charging tho and cant get battery percentage`
`usb in gadget mode for usb network or usb serial mode`
`maybe usb host mode (i dont have a powered hub to test)`
`i2c`
`internal storage (see bugs section)`


#What doesnt work
`bluetooth`
`calls & sms & mobile data`
`display (it shows something but its a framebuffer taken over from bootloader someone would need to write a proper panel driver)`
`touchscreen`
`audio`
`thinq button`
`camera`
`sdcard`
`fingerprint`
`nfc`
`wireless charging`


#Bugs
`Ufs will throw random IO errors and sometimes just refuse to work at all , it can happen on boot or after 12 hours im not smart enough to debug it `

`Wifi wont read the proper mac adress and thus use a random one , at least on my router (Fritz!Box 6591 Cable) this causes IP adresses to "hog up" WORKAROUND: set a static IP`




