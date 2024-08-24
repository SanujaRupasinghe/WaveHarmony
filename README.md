# WaveHarmony
Real Time Audio Spectrum Analyzer
(Analog Project)


Welcome to **WaveHarmony**, an organization dedicated to developing innovative audio spectrum analyzer solutions. This repository contains the main project for our Real-Time Audio Spectrum Analyzer (Analog Project).

## Repository Overview

This is the main repository for the WaveHarmony organization. It provides the core implementation and information about our audio spectrum analyzer project.

### Organization Repositories

For more detailed information and access to specific parts of the project, please visit the following repositories:

- [Documentation](https://github.com/Wave-Harmony/Documentation): Comprehensive documentation for the project.
- [Circuit And Simulation](https://github.com/Wave-Harmony/Circuit_And_Simulation): Details on circuit designs and simulation results.
- [PCB](https://github.com/Wave-Harmony/PCB): PCB designs and layout files.
- [Enclosure](https://github.com/Wave-Harmony/Enclosure): Information on the physical enclosure and design.

## License

This project is licensed under the [MIT License](LICENSE).

## Circuit And Simulation

### File
Simulation files are located at:
`WaveHarmoney/Circuit_And_Simulation/Simulations/Filters.asc`

### Filter Type
10 Band Pass Filters (BPFs) were designed with:
- **Response**: Butterworth, **Topology**: Multiple Feedback (MFB), **Gain (a)**: 2, **Q factor (Q)**: 4, **Capacitor (C)**: 10nF

![Filter Design](https://github.com/WaveHarmoney/Circuit_And_Simulation/assets/123849272/fc1f038a-f2d3-45eb-b379-b43aec21d33e)

### Calculations
Component values (R1, R2, R3) were determined via software. Due to unavailability of exact resistor values, closest matches were used.

![Calculated Values](https://github.com/WaveHarmoney/Circuit_And_Simulation/assets/123849272/328bdd59-d260-4407-832f-706940fab105)
![Resistor Selection](https://github.com/WaveHarmoney/Circuit_And_Simulation/assets/123849272/f7b2c0c7-9856-41eb-b7b0-38569618ba83)

### Simulation Results
Simulations conducted with LTSpice show results for the 10 filters with selected resistors.

![Simulation Result 1](https://github.com/WaveHarmoney/Circuit_And_Simulation/assets/123849272/ac3122b6-5987-4566-8477-98a3c84aab75)
![Simulation Result 2](https://github.com/WaveHarmoney/Circuit_And_Simulation/assets/123849272/789557cd-6775-45cc-b17b-6fb1714a0ffb)
<img src="https://github.com/WaveHarmoney/Circuit_And_Simulation/assets/123849272/41a5b51e-c46f-4c25-a34c-5724f56e262a" width="50%" height="50%" />

## PCB

1. **Power Supply**: Converts AC input to regulated +12V and -12V DC outputs.
2. **Filter + LED Driver**: Filters input signals and drives LEDs based on the processed signal.

### Overview

- **Power Supply**: Provides stable DC voltage from an AC source.
- **Filter + LED Driver**: Processes signals to control LEDs.

### Usage

1. **Power Supply**:
   - Connect AC inputs to the designated terminals for DC output.

2. **Filter + LED Driver**:
   - Connect the signal input to process and drive LEDs.

### Final Image

<img src="https://github.com/user-attachments/assets/1f643d1d-6f29-4316-8b61-22522ea7924b" width="50%" />


## Enclosure
This project features a Real-Time Audio Spectrum Analyzer with a custom enclosure made from wood and acrylic. Due to the size constraints, 3D printing was not feasible, leading to a combination of materials for durability and aesthetics.

### Acrylic Towers
- **Materials**:
  - **Black Acrylic**: Forms the outer structure, **Transparent Acrylic Cubes**: House the LEDs.
- **Assembly**:
  - 100 transparent acrylic cubes held by a black acrylic outline and cube holder, Assembled with acrylic glue.

### LED Configuration
- **Choice**: Individual LEDs driven by LED driver ICs., **Reasoning**: Allows precise placement and better visual output compared to LED strips.


### Dimensions and Pictures

<table>
  <tr>
    <td><img src="https://github.com/WaveHarmoney/Enclosure/assets/123849272/d42298b4-bad5-46e0-b73d-1fd29394d01e" width="400" height="300" /></td>
    <td><img src="https://github.com/WaveHarmoney/Enclosure/assets/123849272/9d295d4f-dda4-487f-9ad6-bb9f489fa8f7" width="400" height="300" /></td>
  </tr>
  <tr>
    <td><img src="https://github.com/WaveHarmoney/Enclosure/assets/123849272/895c41bf-cd7a-4b71-97d7-5b1fa4904fb3" width="400" height="300" /></td>
    <td><img src="https://github.com/WaveHarmoney/Enclosure/assets/123849272/00a8f8e4-3baf-485c-ae8e-115806f69543" width="400" height="300" /></td>
  </tr>
</table>



## Documentation
This contains all the reports and resources related to the Waveharmony Real Time Audio Spectrum Visualized Analog Project. 
Contents
- Pictures
- Videos
- Project Proposal Report
- Finalized Project Report

---


