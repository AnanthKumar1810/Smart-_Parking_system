# 🚗 Smart Parking System using ESP8266

## 📌 Project Concept

The Smart Parking System is an automated parking management solution
designed to monitor parking slot availability and control vehicle entry
without human intervention.

The system uses IR sensors to detect whether a parking slot is occupied
or vacant. An ESP8266 microcontroller processes the sensor data, updates
slot availability in real time, and controls a servo motor that acts as
the parking gate. A 16x2 LCD display provides clear information about
available parking spaces.

This project demonstrates how embedded systems and IoT-enabled
microcontrollers can be used to solve real-world parking congestion
problems efficiently and cost-effectively.

------------------------------------------------------------------------

## 🛠️ Components and Their Roles

### 1️⃣ ESP8266 (NodeMCU)

-   Acts as the main controller of the system.
-   Reads input from IR sensors.
-   Calculates available parking slots.
-   Controls the servo motor.
-   Updates information on the LCD display.

### 2️⃣ IR Sensors

-   Installed in each parking slot.
-   Detect the presence of a vehicle using infrared reflection.
-   Send HIGH/LOW signals to ESP8266 based on slot occupancy.

### 3️⃣ Servo Motor

-   Functions as the entry gate.
-   Opens automatically when parking slots are available.
-   Remains closed when all slots are occupied.

### 4️⃣ 16x2 LCD Display

-   Displays total number of slots.
-   Shows available slot count.
-   Indicates parking status (Available / Parking Full).

### 5️⃣ Power Supply & Connecting Wires

-   Provide necessary voltage and connectivity between components.

------------------------------------------------------------------------

## ⚙️ Working Process

1.  IR sensors continuously monitor each parking slot.
2.  When a vehicle occupies a slot, the sensor detects it and sends a
    signal to the ESP8266.
3.  The ESP8266 updates the internal count of available slots.
4.  The LCD display shows real-time parking availability.
5.  If at least one slot is available, the servo motor opens the gate to
    allow vehicle entry.
6.  If all slots are full, the gate remains closed and the display shows
    "Parking Full".

------------------------------------------------------------------------

## 🚀 Key Features

-   Real-time parking slot detection\
-   Automatic gate control\
-   Live availability display\
-   Fully automated operation\
-   Low-cost and scalable design\
-   IoT-ready (Wi-Fi capable via ESP8266)

------------------------------------------------------------------------

## 🌍 Applications

-   Shopping malls\
-   Office complexes\
-   Residential apartments\
-   Educational institutions\
-   Public parking areas
