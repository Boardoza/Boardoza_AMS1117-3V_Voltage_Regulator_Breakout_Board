# Boardoza AMS1117-3V Voltage Regulator Breakout Board
The AMS1117 is a series of low dropout (LDO) voltage regulators with a fixed and adjustable voltage output. It's widely used in power management applications to provide a stable and precise voltage, especially when battery life is important.

| Front Side | Back Side |
| :---: | :---: |
| ![AMS1117-3 Front](./assets/AMS1117-3V%20Front.png)| ![AMS1117-3 Back](./assets/AMS1117-3V%20Back.png)|

---
## Key Features
- Fixed Output: AMS1117 - 3.3 has fixed output voltage 3.3V.
- Current Capability: It can deliver up to 1A of output current, making it suitable for many low-power applications.
- Low Dropout: Typically requires only 1.2V difference between the input and output voltage at maximum load, facilitating higher efficiency.
- Protection Features: Includes built-in overcurrent protection, thermal overload protection, and safe area protection.
- Quiescent Current: Low quiescent current (drawn by the regulator itself), typically around 5mA, which is beneficial for battery-powered devices.
- Noise Reduction: Output noise and ripple are minimal, but additional filtering cap can be added on the output for noise-sensitive applications.

---
## Technical Specifications

**Input Voltage:**	5V ~ 12V

**Functions:** Low Dropout Voltage Regulator

**Output Voltage:** 3.3V

**Output Current:** 1A

**Operating Junction Temperature:** -40°C to +125°C

**Board Dimensions:**	20mm x 40mm

---
## Board Pinout

| J1 & J3 Pin Number | Pin Name | Description |
| :---: | --- | --- |
| 1 | VIN | Voltage Input |
| 2 | GND | Ground |

| J2 Pin Number | Pin Name | Description |
| --- | --- | --- |
| 1 | GND | Ground |
| 2 | VOUT | Voltage Output |

| J4 Pin Number | Pin Name | Description |
| --- | --- | --- |
| 1 | VOUT | Voltage Output |
| 2 | GND | Ground |

---
## Board Dimensions
<img src="./assets/AMS1117-3 Dimension.png" alt="AMS1117 3.3V Dimension" width="430"/>

---
## Step Files

[Boardoza AMS1117 3.3V.step](https://boardoza.com/stepfiles/AMS1117-3_Var2.step)

---
## Datasheet

[AMS1117 Datasheet.pdf](https://boardoza.com/wp-content/uploads/2024/05/ds1117.pdf)

---
## Version History
- V1.0.0 - Initial Release

---
## Support
- If you have any questions or need support, please contact support@boardoza.com

---
## License

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
