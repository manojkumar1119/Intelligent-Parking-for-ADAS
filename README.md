# Intelligent Parking System for ADAS

A smart parking solution using Bluetooth Low Energy (BLE) beacons and multilateration for accurate indoor and outdoor parking slot detection and navigation.

## Overview

This project implements an intelligent parking system designed to help drivers locate available parking slots efficiently, reducing traffic congestion and vehicular emissions in urban areas. The system uses BLE beacon technology combined with multilateration techniques to provide accurate positioning both indoors and outdoors.

## Key Features

- **Real-time Slot Availability**: Live view of available parking slots
- **Indoor & Outdoor Positioning**: Works in both environments with high accuracy
- **Digital Booking**: Reserve parking slots through the mobile application
- **Energy Efficient**: BLE beacons consume 30% less power than Wi-Fi
- **Accurate Location Tracking**: Uses multilateration for precise positioning
- **User-Friendly Interface**: Intuitive Android application with visual guidance

## Technology Stack

### Hardware Components
- **BLE Beacons**: Transmit location signals (10m range coverage)
- **NodeMCU (ESP8266)**: IoT controller for data processing
- **IR Sensors**: Detect parking slot occupancy status

### Software Components
- **Android Mobile Application**: User interface for booking and navigation
- **Firebase Realtime Database**: Cloud-hosted NoSQL database for real-time data sync
- **Multilateration Algorithm**: Calculate user position from beacon signals

### Technologies Used
- Bluetooth Low Energy (BLE)
- Internet of Things (IoT)
- Firebase Cloud Services
- RSSI (Received Signal Strength Indicator)
- Multilateration positioning technique

### Positioning Method
**Multilateration**: Uses distance measurements from multiple BLE beacons to determine exact user position without requiring angle measurements. Requires:
- 3 beacons for 2D positioning
- 4 beacons for 3D positioning

## System Architecture

### Main Components

1. **NoSQL Database (Firebase)**
   - Stores parking slot data
   - Synchronizes data in real-time
   - Manages user profiles and bookings

2. **User Profile**
   - Saves vehicle information
   - Stores payment details
   - Tracks parking preferences
   - Provides personalized recommendations

3. **Hardware Layer**
   - IR sensors detect slot occupancy
   - NodeMCU processes sensor data
   - BLE beacons broadcast positioning signals

4. **Mobile Application**
   - User and vehicle profiling
   - Parking registration
   - Live slot view
   - RSSI value retrieval and processing
   - Navigation guidance

## Mobile Application Features

- **Main Dashboard**: Overview of parking system
- **Booking Interface**: Reserve slots digitally
- **Slot Availability View**: Real-time status of parking spaces
- **Bluetooth Scanner**: Display RSSI values from nearby beacons
- **Navigation**: Guide users to their reserved parking spot

##  Results

- ✅ Accurate positioning both indoor and outdoor
- ✅ Superior accuracy compared to Wi-Fi and GPS for indoor use
- ✅ Lower power consumption than alternative technologies
- ✅ Sufficient accuracy for parking availability estimation
- ✅ Real-time slot status updates

##  Team

**PSG Institute of Technology and Applied Research, Coimbatore**

- **Dr. G. Santhanamari** - Associate Professor, Department of ECE (Supervisor)
- **Manoj Kumar S** - Final Year ECE Student
- **Anthony Pal Clintan A** - Final Year ECE Student
- **Rahesh R** - Final Year ECE Student
