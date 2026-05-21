# pg-id-656-main-controller-pcb
Custom PCB controller board for an autonomous wheeled robot featuring **STM32L476RG**
<div align="center">
    <img src="images/photo1.jpeg" width="50%">
</div>


## Project Scope
* **Design:** Mixed-signal schematic and custom 2-layer PCB layout designed in **KiCad 9.0.5**.
* **Hardware:** Microcontroller-driven architecture utilizing an ARM Cortex-M4 **STM32L476RGT6**, an **LSM6DSV16X** 6-axis IMU via I2C, and a **DI6206** 3.3V LDO linear regulator for logic power management.
* **Interfaces:** Features onboard SWD programming header, UART comunication port, motor driver connectors, encoder inputs, status LEDs, and user buttons.
* **Assembly:** Surface-mount technology (SMT) featuring 0603 and 0805 passive components, LQFP-64, and LGA-14 IC packages.

### pcb photos and renders:
<div style="display: flex; gap: 10px;">
  <img src="images/robot-pcb-3Dview_1.png" width="45%">
  <img src="images/robot-pcb-3Dview_2.png" width="45%">
</div>

<div style="display: flex; gap: 10px;">
  <img src="images/photo2.jpeg" width="45%">
  <img src="images/photo3.jpeg" width="45%">
</div>


### pcb layout:
<div style="display: flex; gap: 10px;">
  <img src="images/robot-pcb-layout_1.png" width="45%">
  <img src="images/robot-pcb-layout_2.png" width="45%">
</div>
<div style="display: flex; gap: 10px;">
  <img src="images/photo4.jpeg" width="45%">
  <img src="images/photo5.jpeg" width="45%">
</div>


### circuit diagram:
<div style="display: flex; gap: 10px;">
  <img src="images/robot-schematic.png" width="90%">
</div>




## Repository Structure
* `pg-id656.kicad_pro` – Main KiCad project file.
* `pg-id656.kicad_sch` – Schematic source file.
* `pg-id656.kicad_pcb` – PCB layout source file.
* `/images` – PCB 3D renders, schematic exports, and physical project photos.