# Intelligent Parking for ADAS  

## Overview
An Intelligent Parking System for **Advanced Driver Assistance Systems (ADAS)** using **Bluetooth Low Energy (BLE) beacons** and **Multilateration** for accurate indoor and outdoor parking slot detection. It reduces traffic congestion and provides a seamless parking experience through a smartphone app.  

## Key Features
- **BLE Beacons:** Low power, accurate location tracking.  
- **Multilateration Technique:** Calculates user location using distance from beacons.  
- **Android App:** Book slots, view availability, and navigate to parking slots.  
- **Firebase Database:** Real-time data storage for slot availability and user profiles.  

## Technologies Used
- **Bluetooth Low Energy (BLE)** for location tracking.  
- **Multilateration** for accurate distance estimation.  
- **Firebase Realtime Database** for real-time data sync.  
- **Android App Development** using Java.  
- **NodeMCU** and **IR sensors** for slot detection.  

## Installation and Setup
1. **Hardware Setup:**
   - Place BLE beacons in parking area corners.  
   - Connect IR sensors to NodeMCU for slot detection.  

2. **Firebase Configuration:**
   - Set up Firebase Realtime Database.  
   - Add `google-services.json` to the Android app.  

