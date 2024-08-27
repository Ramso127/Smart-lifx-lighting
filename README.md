# Smart LIFX Lighting Controller

This project aims to create an IoT-based smart lighting system that autonomously adjusts the brightness of a LIFX LED light based on the ambient light in the room. The system uses a Raspberry Pi 2b, a light sensor, and an Android application to provide a user-friendly interface for controlling the light's intensity.

## Overview

The smart lighting system consists of several components that work together to achieve a preferred brightness in the room:
- **Python Scripts**: Control the brightness of the LIFX LED lamp and handle MQTT communication.
- **MQTT Protocol**: Facilitates communication between the Raspberry Pi and the Android application.
- **Android Application**: Provides a user interface for setting preferred light intensity and schedules.

## Project Phases

1. **Development Phase**: Hardware setup, code writing for Python scripts, MQTT, and Android application.
2. **Integration Phase**: Integrating MQTT with the Raspberry Pi and Android application.
3. **Testing and Optimization Phase**: Testing the system under different lighting conditions and optimizing the code.

## Features

- **Automatic Brightness Adjustment**: The light's intensity is automatically adjusted based on ambient light readings.
- **User Preferences**: Users can set preferred light intensity and schedules via the Android app.
- **Energy Efficiency**: The system optimizes light usage, saving energy and reducing costs.
- **Default Lighting Schedule**: If no preferences are set, the system uses a default schedule based on the time of day.

## Technologies

- **Python**: For controlling the LIFX LED lamp and handling MQTT communication.
- **Android Studio**: For developing the user interface.
- **MQTT**: For communication between the Raspberry Pi and the Android application.
- **Raspberry Pi 2b**: Acts as the central controller for the system.
- **LIFX API**: For controlling the LED lamp.
- **Putty (SSH)**: For connecting to the Raspberry Pi.
- **Adafruit TSL2591**: Light sensor for measuring ambient light.


## Contributors
- Omar Almassri
- Amir Eihab El Abidou
- Arianit Paso

## Acknowledgments
Thanks to all the libraries and frameworks we use, especially:
- MQTT
- Android Studio
- LIFX API
