# Python Learning Roadmap — Progress and All Levels

**Purpose:** Build practical Python ability for real projects, with a long-term emphasis on robotics engineering and entrepreneurship. This roadmap is designed to progress from the learner's current early-beginner stage to building complete applications. It is a plan, not a claim that every topic is already mastered.

**Learning approach:** Prefer short explanations followed by independent mini-projects. Do not give hints unless requested. Check understanding by reviewing working code and reasoning, not by merely marking a topic as seen.

## Current position (17 October 2026)

The learner has studied or practised:
- Variables, basic data types, `print()`, `input()`
- Arithmetic and assignment operators, including `+=` and `-=`
- `if`, `elif`, `else`, comparisons and basic logic
- `for` loops
- Lists and the `in` operator
- `enumerate()`, `break`, and `continue`
- Introductory dictionaries
- Basic functions, including parameters and `return`
- Introductory `try` / `except`

These are **studied/practised**, not all formally assessed as mastered. Strengthen them through combined problems.

## Level 1 — Core Python fundamentals (current level)

Topics:
1. Variables, values, data types, conversion, input/output
2. Strings and string operations
3. Numbers, arithmetic, assignment, comparison and logical operators
4. Conditions: `if`, `elif`, `else`
5. Loops: `for`, `while`, nested loops
6. Loop control: `break`, `continue`, loop `else`
7. Collections: lists, tuples, sets, dictionaries
8. Indexing, slicing, membership and `enumerate()`
9. Functions, parameters, arguments, return values and scope
10. Basic exception handling and input validation
11. Reading tracebacks and basic debugging

**Immediate next steps:** practise `while`; combine it with conditions, `break`, and `continue`; learn loop `else`; reinforce functions and dictionaries; practise strings and list operations; improve error handling.

Starter projects:
- Shopping calculator
- Robot battery monitor
- Student marks manager
- Number-guessing game
- Menu-driven calculator

**Level completion evidence:** independently build a menu-driven program that validates input, uses functions and collections, handles errors, and runs repeatedly without crashing on ordinary invalid input.

## Level 2 — Write complete, maintainable Python programs

Topics:
1. Function design and variable scope
2. Modules and imports
3. File and folder operations
4. Text files and safe file handling
5. JSON read/write for structured data
6. List/dictionary comprehensions and useful built-ins
7. Classes, objects, methods and attributes
8. Object-oriented design basics
9. Exceptions and custom errors
10. Debugging, logging and automated tests
11. Virtual environments and package installation where supported
12. Project structure, documentation and Git basics

Projects:
- Notes app with saved data
- Student record manager
- Inventory tracker
- Modular command-line productivity tool

**Level completion evidence:** create a multi-file application that persists data, handles invalid input, and has repeatable tests.

## Level 3 — Graphics, animation and games

Topics:
1. Coordinates, screen space and drawing
2. Event loops and frame updates
3. Keyboard/mouse events
4. Movement, velocity and basic timing
5. Collision detection
6. Images, sound and simple UI
7. Animation states and object management
8. Separating application logic from rendering

Possible library: Pygame, when the environment supports it.

Projects:
- Animated bouncing ball
- Moving robot visualisation
- Battery and sensor dashboard
- Small 2D game
- Physics demonstration

**Level completion evidence:** build a responsive graphical project with animation, input handling and organised code.

## Level 4 — Python for robotics

Learn alongside appropriate mathematics, physics and electronics:
1. Functions that represent robot behaviours
2. Coordinates, angles, vectors and geometry basics
3. Motion, speed, distance and timing calculations
4. Sensor data representation and filtering basics
5. State machines and event-driven behaviour
6. Simulating motors, sensors and battery levels
7. Serial communication concepts
8. Microcontroller workflows and hardware constraints
9. Testing simulated behaviours
10. Basic feedback/control concepts
11. ESP32 and other board integration using compatible firmware/tools
12. Safety, power, voltage and wiring fundamentals

Projects:
- Robot movement simulator
- Distance-sensor simulator
- Battery-monitoring system
- Obstacle-detection logic
- Motor-speed calculator
- Sensor log analyser

Note: Python on an Android phone cannot by itself control physical hardware. Hardware projects require a compatible board, firmware, communication method and suitable development environment. Some ESP32 workflows use MicroPython; others use C/C++ or other tools.

**Level completion evidence:** explain and test a robot behaviour in simulation, then connect it to real hardware when suitable equipment and setup are available.

## Level 5 — APIs, networking and data

Topics:
1. HTTP and request/response basics
2. JSON APIs
3. API clients and the `requests` library where supported
4. Timeouts, status codes and network errors
5. Data cleaning and transformation
6. CSV and structured data
7. SQLite and SQL basics
8. Basic data visualisation
9. Secrets and environment variables (never hard-code private API keys)

Projects:
- Weather API client
- Personal expense or activity tracker
- CSV data analyser
- Local database-backed records app

**Level completion evidence:** retrieve data from an API or local dataset, validate it, store it safely, and explain common failure cases.

## Level 6 — Choose an application specialisation

Do not learn every branch at once. Choose based on a project.

- **Web apps/APIs:** Flask or FastAPI; routes, validation, HTTP, authentication concepts and databases.
- **Data analysis:** NumPy, pandas and visualisation.
- **AI/ML:** data preparation, model evaluation, and then appropriate ML libraries.
- **Automation:** filesystem work, repeatable scripts, APIs and scheduled tasks.
- **Robotics:** sensor processing, simulation, serial communication and robotics libraries.
- **Games/visualisation:** Pygame and graphics concepts.

Projects should solve a real need and be small enough to finish, test and improve.

## Level 7 — Professional engineering practices

Topics:
1. Git and GitHub workflows
2. Unit and integration tests
3. Debugging and logging
4. Readable naming and code organisation
5. Documentation and reproducible setup
6. Dependency and environment management
7. Basic security: protect secrets, validate inputs, avoid unsafe execution
8. Performance and resource awareness
9. Code review and incremental improvement
10. Deployment when relevant to the chosen project

**Level completion evidence:** another person can understand, run, test and maintain the project from its documentation.

## Suggested sequence

1. Finish Level 1 fundamentals and prove them through combined programs.
2. Complete Level 2 file-backed projects.
3. Learn graphics/animation (Level 3) if visual motivation is useful.
4. Progress into robotics (Level 4), continuing maths and electronics.
5. Learn APIs, data and databases as projects require them (Level 5).
6. Select a specialisation (Level 6).
7. Apply professional practices throughout, formalising them in Level 7.

Levels can overlap; this is a flexible roadmap, not a rigid prerequisite chain.

## Progress tracking rules

Use these labels for each topic:
- **Not started**
- **Introduced**
- **Practised**
- **Independently demonstrated**
- **Needs review**

Only mark a topic **Independently demonstrated** after the learner solves a suitable task without hints and can explain the solution. Reassess older topics through projects instead of repeating lessons unnecessarily.

## Current next challenge

Build a robot battery monitor:
- Start with `battery = 100`.
- Each scan uses 15 percentage points.
- Use a `while` loop to repeat scans.
- Print the battery after each scan.
- Stop when the battery is below 30%.
- Use `-=`, an `if` condition and `break` where appropriate.

The learner should attempt it independently; do not reveal hints unless asked.

## Long-term outcome

Become capable of designing, building, debugging, testing and explaining useful Python programs, then apply that ability to robotics, visual simulations, automation and entrepreneurial products.
