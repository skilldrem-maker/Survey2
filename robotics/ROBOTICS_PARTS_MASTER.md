# Robotics Parts Master Reference

A practical parts checklist for learning robotics from beginner to AI/autonomous robots.

## 1. Controller / Computing
- Arduino Uno / Nano — beginner microcontroller projects
- ESP32 — Wi-Fi/Bluetooth + microcontroller projects
- Raspberry Pi — Linux, Python, camera and higher-level robotics
- NVIDIA Jetson (later) — computer vision and AI inference
- USB cable, microSD card, appropriate power supply

## 2. Electronics Basics
- Breadboard
- Jumper wires: male-male, male-female, female-female
- Resistors: 220Ω, 330Ω, 1kΩ, 10kΩ
- LEDs
- Push buttons
- Potentiometers
- Capacitors
- Diodes
- Transistors / MOSFET modules
- Logic-level voltage converter (when required)
- Multimeter

## 3. Motors and Motion
- TT geared DC motors
- N20 geared motors
- Servo motor (SG90/MG90S)
- Stepper motor + driver
- Motor driver: TB6612FNG or similar efficient H-bridge
- Wheels
- Caster wheel
- Couplers, gears and mechanical brackets

## 4. Sensors
### Distance / Obstacle
- HC-SR04 ultrasonic sensor
- VL53L0X / VL53L1X time-of-flight sensor
- IR obstacle sensors

### Light / Environment
- LDR
- DHT11/DHT22 temperature-humidity sensor
- BMP280/BME280 pressure sensor

### Motion / Orientation
- MPU6050 IMU
- Better IMU modules for advanced projects
- Wheel encoders

### Line Following
- IR reflectance sensor array

### Vision
- USB webcam
- Raspberry Pi Camera / compatible CSI camera
- Depth camera (advanced)

## 5. Power
- AA battery holder for safe beginner experiments
- Rechargeable battery pack appropriate for the project
- 5V/regulated DC-DC buck converter
- Power switch
- Fuse / protection where appropriate
- Battery voltage monitor
- Correct connectors and wires

**Safety:** Never connect a battery directly to a component unless its voltage/current requirements explicitly allow it. Use regulated power and common ground correctly.

## 6. Robot Chassis / Mechanical Parts
- 2WD or 4WD robot chassis
- Acrylic/metal/3D-printed plates
- Motor brackets
- Standoffs and spacers
- M2/M3/M4 screws, nuts and washers
- Bearings
- Rubber wheels
- Cable ties / cable management
- Small screwdriver set and pliers

## 7. Communication
- USB serial
- Bluetooth module (e.g., HC-05, where appropriate)
- ESP32 Wi-Fi/Bluetooth
- NRF24L01 (optional)
- Ethernet/Wi-Fi for Raspberry Pi

## 8. AI / Computer Vision (Later Stage)
- Raspberry Pi or Jetson-class computer
- Camera
- Adequate storage
- Cooling/heatsink/fan where required
- Microphone for voice projects
- Speaker for voice feedback

## 9. Tools Worth Owning
- Digital multimeter
- Soldering iron + stand
- Solder and flux
- Wire stripper/cutter
- Precision screwdrivers
- Tweezers
- Heat-shrink tubing
- Breadboard power module
- USB logic analyzer (advanced)
- Solderless test leads

## 10. Recommended Learning Order
1. Breadboard + LEDs + resistors + buttons
2. Arduino/ESP32 digital and analog I/O
3. Sensors
4. Servo and DC motors
5. Motor driver + 2WD robot
6. Encoders and PID basics
7. Raspberry Pi + Linux + Python
8. Camera + computer vision
9. ROS 2 + C++
10. Autonomous navigation, mapping and AI

## 11. Beginner Starter Kit
A compact first kit can contain:
- Arduino Uno/Nano or ESP32
- Breadboard
- Jumper-wire set
- LED/resistor assortment
- Push buttons + potentiometers
- HC-SR04
- MPU6050
- SG90 servo
- 2 TT motors + wheels + caster
- TB6612FNG motor driver
- Battery holder / suitable rechargeable pack
- Multimeter

Buy components incrementally rather than purchasing the entire advanced list at once. Check voltage, current, connector type and library/software compatibility before buying.
