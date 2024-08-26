# Electric Vehicle Battery Management System (EV BMS)

## Project Overview

This project is an Electric Vehicle Battery Management System (EV BMS) designed to monitor and manage the battery pack in an electric vehicle. The system ensures the safety, efficiency, and longevity of the battery by monitoring various parameters, such as voltage, temperature, and state of charge.

## Features

- **Real-time Monitoring:** Continuously monitors voltage, temperature, and other critical parameters.
- **Safety Protections:** Includes over-voltage, under-voltage, over-temperature, and under-temperature protections.
- **State of Charge (SOC) Estimation:** Accurately calculates the remaining charge in the battery pack.
- **Data Logging:** Logs all the monitored data for future analysis and diagnostics.
- **User Interface:** Provides a graphical user interface (GUI) for easy monitoring and control.

## Technologies Used

- Microcontroller:Arduino STM32 microcontroller
- Sensors:voltage sensor, current sensor, DHT!! sensor for tempreature readings
- Communication Protocols:
     I2C (Inter-Integrated Circuit):Used for communication between the microcontroller and various sensors (e.g., temperature sensors, voltage sensors).
                                    Suitable for short-distance communication within the BMS.
- Programming Language: C

