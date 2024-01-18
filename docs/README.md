# Simple FreeRTOS project

## Overview

This project demonstrates a simple application for controlling and monitoring two LEDs (red and blue) using ESP32. The functionality is divided into different FreeRTOS tasks for better organization and modularity. The tasks include:

- **Control Tasks**: Two tasks (`controlTaskRed` and `controlTaskBlue`) handle the control logic for the red and blue LEDs, respectively.
- **Blink Tasks**: Two tasks (`blinkTaskRed` and `blinkTaskBlue`) implement the blinking functionality for the red and blue LEDs, respectively. 
- **Acknowledgment Task**: The `ackTask` monitors acknowledgment for both buttons.

## Priority
- **Tasks** in this project are assigned priorities using FreeRTOS priorities. The numerical value of the priority increases with the level of priority, where a higher numerical value corresponds to a higher priority.
