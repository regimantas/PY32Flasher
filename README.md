## PY32Flasher
A lightweight and user-friendly tool for flashing PY32 microcontrollers using the STM32 Link V2 programmer. This tool provides an intuitive interface for flashing .hex or .bin files directly to the microcontroller, leveraging the SWD protocol for efficient and reliable programming.

## Downloads
Choose the appropriate version for your platform:
  - **Windows (AMD64):** [Download Py32Flasher](https://github.com/regimantas/PY32Flasher/releases/download/v1.0.0/Py32Flasher-windows.exe)
  - **Linux (AMD64):** [Download Py32Flasher](https://github.com/regimantas/PY32Flasher/releases/download/v1.0.0/Py32Flasher-linux-amd64)
  - **Linux (ARM):** [Download Py32Flasher](https://github.com/regimantas/PY32Flasher/releases/download/v1.0.0/Py32Flasher-linux-arm)

## Screenshot
![PY32 Flasher Screenshot](https://github.com/regimantas/PY32Flasher/blob/main/Ekrano%20kopija%202024-12-23%20205243.png?raw=true)

## Compatibility
- Tested and verified with:
  - **PY32F002A and PY32F030K28T6** microcontrollers
  - STM32 Link V2 programmer (For Windows users needed st link drivers)
  - **PY32 Arduino Core**:
    - To use the PY32 Arduino Core, add the following URL to the Arduino IDE Boards Manager:
      ```
      https://github.com/PY32Duino/Arduino-pack-json-ci/releases/download/Nightly/package_py32_index.json
      ```
    - In Arduino IDE, go to:
      1. **File > Preferences**.
      2. Paste the above URL into the **Additional Board Manager URLs** field.
      3. Open the **Boards Manager** and install the PY32Duino package.
- On WSL (Windows Subsystem for Linux) tested as working on Ubuntu Preview. Normal Ubuntu Have to old librarys.


## License
Licensed under the MIT License. See the [LICENSE](https://github.com/regimantas/PY32Flasher/blob/main/LICENSE) file for more details.
