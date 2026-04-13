# Environmental Exposure Monitoring System

## Overview
This project is a Personal Environmental Monitoring System using ESP32 that calculates a time-based exposure score based on environmental conditions.

## Features
- Air Quality Monitoring (MQ135)
- Temperature Monitoring (BMP280)
- UV Detection (GUVA-S12SD)
- Noise Level Detection (MAX9814)
- Motion Detection (MPU6050)
- OLED Display Output
- Web Dashboard (Wi-Fi)

## Innovation
Unlike traditional systems, this project uses a **time-based exposure model**:
- Exposure increases only in harmful conditions
- Exposure accumulates over time
- Exposure decreases in safe environments

## Exposure Logic
- Short exposure → small impact
- Medium exposure → moderate impact
- Long exposure → high risk (alerts triggered)

## Hardware Used
- ESP32
- MQ135
- BMP280
- GUVA-S12SD
- MAX9814
- MPU6050
- OLED Display

## Future Improvements
- More accurate AQI sensor
- Mobile app integration
- Cloud data storage
