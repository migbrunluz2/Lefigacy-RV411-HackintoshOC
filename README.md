# Lefigacy-RV411-HackintoshOC: An Legacy only OpenCore EFI for the Samsung RV411,as nobody has ever done it before


<img width="640" height="480" alt="image" src="https://github.com/user-attachments/assets/dd8a4b9a-f5f6-45ff-814d-e7f25aaa9971" />


This is a work in progress Opencore EFI for the RV411 model (OTHER MODELS EXCEPT THE AMD MODELS AS ITS FULLY UNSUPPORTED ARE UNTESTED). which its specs are:

CPU: I3 330M (Arrandale)
Audio (Realtek ALC269)
Wi-FI: Atheros AR9285
Trackpad model and type: ELAN PS/2


# YOU **MUST** BOOT THIS EFI VIA LEGACY MODE AS ITS BIOS THROWS "Unregistered Exception Handler" DURING UEFI BOOT

# What works
√ Audio (alcid=3)
√ QE/CI (Little bit of graphical wear/tear when minimizing window)
√ Wi-Fi (Spoofed? to AR9280)
√ Webcam (wow!)
√ In-built keyboard (Very wonky and unresponsive sometimes)
√ In-built Microphone
√ Battery (Is a bit inaccurate)
√ Headphone/Microphone jack
# What does NOT work at the moment..
Trackpad (uses an ELAN PS/2 trackpad model,however ApplePS2SmartTouchpad ignores it and so is VoodooPS2Controller,possibly I2C?)
Sleep (Blank screen during wake-up,however responsive??)
Backlight keys and Backlight,screen dims itself when unplugged
# Unconfirmed?
? HDMI/VGA ports
? SD Cards
? Bluetooth
EFI will be released until i have fixed almost all bugs.
