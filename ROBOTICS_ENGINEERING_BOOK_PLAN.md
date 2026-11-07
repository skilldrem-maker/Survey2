# Robotics Engineering — Combo-Wise Book Plan

**Purpose:** Learn electronics only to the level needed for robotics. Robotics engineering is the main discipline; electronics is a supporting track. This is not a separate electronics-engineering curriculum.

**Structure:** Six combos, studied in parallel. Each combo pairs one electronics-focused book with one robotics-focused book. Books are staged by new skills, while allowing necessary reinforcement.

## Combo 1 — Foundations
- **Electronics:** *Make: Electronics* — Charles Platt
  - Scope: voltage, current, resistance, Ohm's law, LEDs, resistors, capacitors, diodes, transistors, breadboards, basic circuit testing.
- **Robotics:** *Robot Building for Beginners* — David Cook
  - Scope: robot structure, chassis, wheels, motors, mechanical assembly, basic mobile robot concepts.
- **Project:** Build simple low-voltage circuits and study/assemble a basic two-wheel robot.

## Combo 2 — Microcontrollers and mechanisms
- **Electronics:** *Arduino Workshop* — John Boxall
  - Scope: Arduino Uno, digital and analog I/O, basic C/C++, connecting sensors, servo and DC motor interfacing, motor-driver modules.
- **Robotics:** *Making Things Move: DIY Mechanisms for Inventors, Hobbyists, and Artists* — Dustyn Roberts
  - Scope: gears, linkages, mechanisms, motion conversion, mechanical design.
- **Project:** Program a motorised mechanism using an Arduino.

## Combo 3 — Sensors and robot integration
- **Electronics:** *Make: Sensors* — Tero Karvinen, Kimmo Karvinen, and Ville Valtokari
  - Scope: practical sensor selection, wiring, measurement, reading and interpreting sensor data; only sensor electronics needed for robot projects.
- **Robotics:** *Robot Builder's Bonanza* — Gordon McComb
  - Scope: robot platforms, construction, integration of mechanical, electrical and control components.
- **Project:** Build a sensor-based obstacle-detection mobile robot.

## Combo 4 — Connected and programmable robots
- **Electronics:** *Programming the ESP32* — Simon Monk
  - Scope: ESP32 development, MicroPython, GPIO, Wi-Fi/Bluetooth basics, interfacing robot sensors and actuators. Verify the exact edition/title before purchase.
- **Robotics:** *Arduino Robotics* — John-David Warren, Josh Adams, and Harald Molle
  - Scope: practical robot programming, sensor/motor integration, autonomous behaviours and robot projects.
- **Project:** Build a remotely monitored or wirelessly controlled robot.

## Combo 5 — Robot mechanics, motion and control
- **Electronics:** *Arduino Cookbook* — Michael Margolis
  - Scope: practical hardware interfacing, reusable microcontroller techniques, debugging and integration. Use selectively as a reference; do not study unrelated electronics topics.
- **Robotics:** *Modern Robotics: Mechanics, Planning, and Control* — Kevin M. Lynch and Frank C. Park
  - Scope: robot kinematics, dynamics, motion planning, feedback control and mathematical foundations.
- **Project:** Develop a controlled robotic arm or a mobile robot with measured motion.

## Combo 6 — AI and autonomy
- **Electronics:** No new general electronics textbook required.
  - Use the Arduino/ESP32 references from earlier combos only when the robot's hardware requires them. Learn additional electronics on a project-driven basis.
- **Robotics:** *Introduction to AI Robotics*, 2nd edition — Robin R. Murphy
  - Scope: robot perception, sensing, acting, planning, decision-making and autonomous behaviour.
- **Additional software reference:** *Learning ROS for Robotics Programming* — use as a supplementary ROS learning resource; check edition and ROS version compatibility before buying.
- **Project:** Build an autonomous robot that senses its environment, makes decisions and navigates.

## Electronics boundary — what to learn
Learn only what is needed to:
1. Understand and safely use low-voltage DC circuits.
2. Connect and troubleshoot sensors, motors, servos, motor drivers and microcontrollers.
3. Understand power, current limits, grounding, polarity, batteries and regulators for robot systems.
4. Read simple schematics and datasheets.
5. Debug wiring, signals and embedded hardware.
6. Integrate Arduino/ESP32 hardware with robot software.

Do **not** make professional electronics engineering a separate required track. Exclude advanced analogue circuit design, semiconductor physics, VLSI/chip fabrication, power-electronics specialisation and professional PCB engineering unless a specific robotics project later requires them.

## Progression summary

| Combo | Electronics contribution | Robotics contribution |
|---|---|---|
| 1 | Circuit fundamentals | Robot structure and construction |
| 2 | Arduino and hardware interfacing | Mechanisms and motion |
| 3 | Sensors and measurements | Robot integration |
| 4 | ESP32 and wireless hardware | Programmable connected robots |
| 5 | Practical interfacing and debugging | Kinematics, planning and control |
| 6 | Project-specific hardware only | AI and autonomous robotics |

## Study method
- Study both books in a combo in parallel.
- Build a practical project before moving to the next combo.
- Keep separate Electronics-for-Robotics and Robotics Engineering notebooks.
- Do not buy all books at once; start with Combo 1.
- Treat advanced titles as later-stage references, not beginner prerequisites.
- Check current edition, availability, price and compatibility before purchasing.

**End goal:** Independently design, construct, program, test and improve intelligent robots.