---

## Project: ESP32 Wind Turbine Power Generation & Loss System

Explore the fascinating world of renewable energy with this interactive kit! You'll build a miniature wind turbine driven by a fan, and use an ESP32 to measure the electrical power it generates. This project is designed to teach fundamental principles of energy conversion, electrical measurement, and the concept of power loss in a circuit, all within a visually appealing diorama.

### Key Learning Outcomes:

* **Energy Generation Principles*: Understand how kinetic energy (simulated wind) can be converted into electrical energy using a generator.
* **Electrical Measurement*: Learn to accurately measure voltage, current, and calculate instantaneous power output using the INA219 sensor.
* **Energy Efficiency & Loss*: Explore the concept of power loss in a simple circuit and how to quantify conversion inefficiencies.
* **Visual Feedback*: Utilize NeoPixel LEDs to visually represent power generation or other system states.
* **Data Display*: Show real-time power metrics locally on an OLED screen and remotely via a web dashboard.
* **Diorama Construction*: Assemble a custom 3D-printed housing that brings the energy concepts to life with a "wind turbine" and power flow visualization.

### Peripherals Included:

* ESP32 Dev Board
* Small DC Motor/Generator (for wind turbine)
* Small DC Fan (to simulate wind and drive the turbine)
* INA219 Current/Voltage Sensor Module
* Load Resistor (e.g., 10 Ohm, 1/2W)
* 0.96" I2C OLED Display (128x64 pixels)
* Micro-USB Cable
* Breadboard & Jumper Wires
* Custom 3D-printed Diorama Housing (with fan mount, turbine blades, and "power flow" visual elements)
* Small NeoPixel (WS2812B) LED (for visual feedback/diorama lighting)

### Core Functions:

* **Wind Energy Simulation*: The fan drives the motor, generating electrical power.
* **Power Measurement*: Accurately measure generated voltage, current, and calculate instantaneous power output.
* **Power Loss Calculation*: A simplified calculation to demonstrate energy conversion inefficiencies within the system.
* **Local Display*: Show real-time voltage, current, and power metrics on the OLED screen.
* **Web Dashboard*: Host a local web server on the ESP32 to display live and historical power data with basic charts.
* **Visual Status*: Use the NeoPixel LED to provide visual feedback on power generation (e.g., brighter as more power is generated).
* **Serial Output*: Print all power data to the Serial Monitor for detailed analysis.

---