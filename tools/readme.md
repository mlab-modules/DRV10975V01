# Oscilloscope Measurements of Motor Phases

This repository contains oscilloscope measurements of the motor phases using a drill. The drill has two gears, referred to as gear 1 (slow) and gear 2 (fast). Therefore, all files are named with the motor type followed by `_fast` or `_slow` to indicate the corresponding gear.

## Purpose of Measurements

The measurements were conducted to determine the harmonic distortion of the motors. By analyzing the phase data under different gear settings, we can assess the performance and efficiency of the motors.

### Explanation of Files

- **`<Motor_Type>_fast/`**: Contains measurements taken with the drill set to gear 2 (fast ~1300 RPM).
- **`<Motor_Type>_slow/`**: Contains measurements taken with the drill set to gear 1 (slow ~380 RPM).

### Measurements Overview

The following table provides an overview of the oscilloscope measurements for different motor types, displaying images for both slow and fast gears.

| Motor Type        | Slow Gear (Gear 1) Image                          | Fast Gear (Gear 2) Image                          |
|-------------------|---------------------------------------------------|---------------------------------------------------|
| Axi2814-20        | ![Axi2814-20_slow](measurements/Axi2814-20_slow.png) | ![Axi2814-20_fast](measurements/Axi2814-20_fast.png) |
| Axi2814-28        | ![Axi2814-28_slow](measurements/Axi2814-28_slow.png) | ![Axi2814-28_fast](measurements/Axi2814-28_fast.png) |
| Axi2826-10        | ![Axi2826-10_slow](measurements/Axi2826-10_slow.png) | ![Axi2826-10_fast](measurements/Axi2826-10_fast.png) |
| df45l024053-a2    | ![df45l024053-a2_slow](measurements/df45l024053-a2_slow.png) | ![df45l024053-a2_fast](measurements/df45l024053-a2_fast.png) |
| df45m024053-a2    | ![df45m024053-a2_slow](measurements/df45m024053-a2_slow.png) | ![df45m024053-a2_fast](measurements/df45m024053-a2_fast.png) |
| MN4006            | ![MN4006_slow](measurements/MN4006_slow.png)         | ![MN4006_fast](measurements/MN4006_fast.png)         |
| MN5006            | ![MN5006_slow](measurements/MN5006_slow.png)         | ![MN5006_fast](measurements/MN5006_fast.png)         |
