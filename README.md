# Graduation Project: Smart Golf Car Automation System

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Description](#Description)
- [Technologies Used](#technologies-used)
- [System Architecture](#system-architecture)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributors](#contributors)
- [License](#license)

---

## Overview

External self driving device for golf-car is a graduation project developed as part of the requirements for the Bachelor’s degree in Mechatronics Engineering, Benha national University.  

## Description
The **Smart Golf Car Automation System** is a graduation project that transforms any regular golf car into a fully automated, self-driving vehicle.  
Our system is designed as an **external plug-and-play module** that can be attached to existing golf cars, enabling autonomous navigation without permanent modifications.

We also developed a **web-based interface** that allows users to:
- Call the golf car remotely.
- Set the destination or route directly from their device.

The project aims to provide a practical, cost-effective, and user-friendly solution for golf courses, resorts, and private estates.


## Features

- ✅ [Feature 1 — e.g., Real-time object detection]
- ✅ [Feature 2 — e.g., Data logging and visualization]
- ✅ [Feature 3 — e.g., Wireless control via mobile]
- ✅ [Feature 4 — e.g., User-friendly GUI]

## Technologies Used

- **Programming Languages:** C / C++ / Python / JavaScript / HTML /CSS
- **Frameworks & Libraries:** OpenCV, Flask, TensorFlow, React, RTOS
- **Hardware:** High end MP / stm32f407vet6 / Sensors / Actuators / Camera
- **Tools:** Git/ Docker/ SolidWorks/ MatLab

## System Architecture

[Web App] <--(REST API)--> [Server / Backend] <---> [linux  MP ]
         [linux MP]<--(Camera- Trained AI model)-->[Real-time MC for bare metal ]-- [Golf Car Motors & Sensors]
---