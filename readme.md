![20230813_202808](https://github.com/Ampersand-Alexander/ModernThroneKB/assets/60246286/f4839456-e7b9-4b4e-900f-8dcefe9b476e)# handwired/modernthrone

![20230813_202808](https://github.com/Ampersand-Alexander/ModernThroneKB/assets/60246286/8c7cede6-1af3-4d54-9a85-e4e3967fe7ce)

![20230815_161239](https://github.com/Ampersand-Alexander/ModernThroneKB/assets/60246286/341a8bc1-0a96-4261-a34f-74ab7f8583e3)

![20230823_232951](https://github.com/Ampersand-Alexander/ModernThroneKB/assets/60246286/61064b7b-a118-470f-8da4-f721eed6c0a4)

![handwired/modernthrone](imgur.com image replace me!)

*Hello 👋, this is the first handwired keyboard I have created the ModernThrone. It is a 69 key layout promoting a solenoid. It uses the RP2040 microcontroller. QMK *

* Keyboard Maintainer: [Alexander Tran](https://github.com/FullyAscended)
* Hardware Supported: *RP2040*
* Hardware Availability: *[Stampy](https://keeb.io/products/stampy-rp2040-usb-c-controller-board-for-handwiring)*

Make example for this keyboard (after setting up your build environment):

    make handwired/modernthrone:default

Flashing example for this keyboard:

    make handwired/modernthrone:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
