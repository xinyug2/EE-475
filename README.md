# Smart-Bartender
This project develops an automated alcohol dispenser system that monitors a user’s blood alcohol content and pours them drinks to stay under a specific BAC level. The ID recognition system verifies a user’s age by detecting a horizontal driver’s license using algorithms based on Yolo network. A breath analyzer is integrated with Arduino to measure users’ breath alcohol concentration The dispenser system is driven by air pressure created using motor to dispense appropriate amount of alcohol and non-alcohol. LED screen is used to provide users with instructions and guidance.

## Table of Contents
- [System Overview](#system-overview)
- [Hardware Setup](#hardware-setup)

## System Overview
- System Computer: MAXI_BIT, master device to all other subsystems
- Card Scanner: MAXI_BIT, scans an ID and extracts information 
- Breathlyzer: BAC, measure BAC in breath
- Dispenser Subsystem: Arduino nano, Air pumps, dispense certain amount and type of drink based on input
- Info Display: LCD, shares status of the system including info from "Card Scanner" and "dispenser subsystem"

## Hardware Setup
- Sipeed MAix BiT with Camera
- Arduino Nano
- TFT LCD Screen with FPC Connectio
- Other Components: Air pump DC motors, Digital Relay Switch
