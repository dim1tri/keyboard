# Configuration of my DZ60 keyboard

### Steps to upload firmware to the keyboard
* Make sure you have installed *dfu-programmer*
* `lsusb` (make sure your keyboard is attached in bootloader mode)
* `sudo dfu-programmer atmega32u4 erase`
* `sudo dfu-programmer atmega32u4 flash firmware.hex`
* `sudo dfu-programmer atmega32u4 reset`

### Steps to update layout:
* Upload `keyboard.json` file to https://config.qmk.fm
* Edit keyboard layout
* Build and download the firmware `.hex` file
* Follow the steps above to upload firmware to the keyboard

Current layout:
![Layer 1](https://github.com/dim1tri/keyboard/layer1.png)
![Layer 2](https://github.com/dim1tri/keyboard/layer2.png)
![Layer 3](https://github.com/dim1tri/keyboard/layer3.png)

