# handwired/20keypad/v1

![handwired/20keypad/v1](imgur.com image replace me!)

* Keyboard Maintainer: [Said Mrini](https://github.com/smrini)
* Hardware Supported: *rp2040zero*
* Hardware Availability:
    * MicroController: rp2040zero
    * Diodes:1N4148
    * 3D files: Printables
  
Flashing example for this keyboard:

    qmk flash -kb handwired/20keypad/v1 -km default


## Bootloader

Enter the bootloader in 3 ways:

* **Physical reset button**: there are 2 buttons on the back of the PCB - press and hold the Boot button, don't leave it yet, press the reset button one time, after you leave it, remove your hand from the boot button.
* **Keycode in layout**: Press and hold the 3rd key from left on the top row then press the last key on the same row. The LED will blink 3 times, then hold in red, till the flash is complete
