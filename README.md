## PY32Flasher
A lightweight and user-friendly tool for flashing PY32 microcontrollers using the STM32 Link V2 programmer. This tool provides an intuitive interface for flashing .hex or .bin files directly to the microcontroller, leveraging the SWD protocol for efficient and reliable programming.

## Compatibility
- Tested and verified with:
  - **PY32F002A** microcontroller
  - STM32 Link V2 programmer
  - **PY32 Arduino Core**:
    - To use the PY32 Arduino Core, add the following URL to the Arduino IDE Boards Manager:
      ```
      https://github.com/PY32Duino/Arduino-pack-json-ci/releases/download/Nightly/package_py32_index.json
      ```
    - In Arduino IDE, go to:
      1. **File > Preferences**.
      2. Paste the above URL into the **Additional Board Manager URLs** field.
      3. Open the **Boards Manager** and install the PY32Duino package.


