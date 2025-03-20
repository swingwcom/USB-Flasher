# USB-Flasher
A Web Serial tool for updating your ESP microcontroller

# Javascript implementation of esptool
This repository contains a Javascript implementation of [esptool](https://github.com/espressif/esptool), a serial flasher utility for Espressif chips. `esptool-js` is based on [Web Serial API](https://wicg.github.io/serial/) and works in Google Chrome and Microsoft Edge [version 89 or later](https://developer.mozilla.org/en-US/docs/Web/API/Serial#browser_compatibility) browsers. 

Code has been customized to limit the options that a user has to deal with (removed flash erase button, pre-set the flash offset to 0x10000, pre-set the baud rates and added logos and links to the SwingW.com update instructions).

## License
The code in this repository is Copyright (c) 2023 Espressif Systems (Shanghai) Co. Ltd. It is licensed under Apache 2.0 license, as described in [LICENSE](https://github.com/espressif/esptool-js/blob/main/LICENSE) file. Midififations to the code for this repositry were done by Swingw, LLC.
