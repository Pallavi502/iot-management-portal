## IoT Management Portal

## Description
A system designed to monitor and manage IoT devices centrally.

## Features
- Device monitoring
- Data collection
- Centralized control system

## Technologies
- Python
- MySQL
- Figma
- HTML
- CSS
- Javascript

## My Role
- Backend logic
- System design

## System Workflow

### 1. Login System
- User enters username and password  
- System validates credentials using database  
- If valid, user is redirected to dashboard  
- If invalid, error message is displayed  

### 2. Device Registration
- User inputs Device ID, Device Name, and Owner  
- System checks for duplicate Device ID  
- If unique, device is added to database  
- Otherwise, user is notified  

### 3. Device Monitoring
- System retrieves device data from database  
- Displays real-time device status  
- Alerts user if any device is offline  

### 4. Device Control
- User selects device and sends command  
- System communicates with device  
- Displays success or failure response  

### 5. Report Generation
- User selects time range and devices  
- System fetches historical data  
- Generates usage and status reports  
- Displays results in table or graph format

## System Design Overview
The system follows a centralized architecture where all IoT devices are managed through a backend server. It handles authentication, device communication, data storage, and reporting in a structured workflow.
