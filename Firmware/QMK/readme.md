# bigsaltykeypad_5rol

![bigsaltykeypad_5rol](https://github.com/LRGuess/BigSaltyKeypad-5ROL/blob/main/Assets/Hackpad.png)

A 5 Key marcopad with a rotary encoder, OLED display and 5LEDs.

* Keyboard Maintainer: [Liam Ramirez-Guess](https://github.com/LRGuess)
* Designed with a [Custom PCB](https://github.com/LRGuess/BigSaltyKeypad-5ROL/tree/main/PCB).

Make example for this keyboard (after setting up your build environment):

    make bigsaltykeypad_5rol:default

Flashing example for this keyboard:

    make bigsaltykeypad_5rol:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
