---

## Project: ESP32 Automated Plant Watering & Grow Light System

This project focuses on creating an automated system to care for indoor plants. An ESP32 will monitor soil moisture levels and ambient light, controlling a water pump to irrigate the plants as needed and managing a grow light to ensure optimal photosynthetic activity. This system combines environmental sensing with automated responses for practical plant care.

### Key Learning Outcomes:

*   **Sensor Integration**: Using soil moisture sensors to determine plant watering needs and LDRs or light sensors to assess ambient light conditions.
*   **Actuator Control**: Managing a water pump (likely via a relay or MOSFET) for irrigation and controlling an LED grow light.
*   **Automation Logic**: Developing algorithms to decide when and how much to water, and when to activate/deactivate the grow light based on sensor readings and set schedules.
*   **Power Management**: Handling the power requirements for the ESP32, sensors, pump, and grow light.
*   **Plant Science Basics**: Understanding basic plant needs for water and light.
*   **Data Logging & Display (Optional)**: Showing current moisture levels, light status, and watering history on an OLED display or a web interface.

### Peripherals (Conceptual):

*   ESP32 Dev Board
*   Capacitive Soil Moisture Sensor(s)
*   Small Water Pump (e.g., 5V submersible pump)
*   Relay Module or MOSFET to control the pump
*   LED Grow Light (strip or small panel)
*   MOSFET or Relay for grow light control (if not built-in)
*   LDR (Light Dependent Resistor) or a dedicated light sensor (e.g., BH1750)
*   Tubing for water delivery
*   Small Water Reservoir
*   OLED Display (e.g., 0.96" I2C) (Optional)
*   Power Supply suitable for all components
*   Micro-USB Cable
*   Breadboard & Jumper Wires
*   Custom 3D-printed enclosure for components and plant integration.

### Core Functions:

*   **Soil Moisture Monitoring**: Periodically read soil moisture levels.
*   **Automated Watering**: Activate the water pump for a set duration if moisture drops below a threshold.
*   **Ambient Light Sensing**: Monitor ambient light to determine if supplementary grow light is needed.
*   **Grow Light Control**: Activate the grow light based on a schedule or low ambient light conditions.
*   **Manual Override (Optional)**: Allow manual activation of the pump or light via buttons or a web interface.
*   **Status Display (Optional)**: Show current sensor readings and system status on an OLED screen.
*   **Web Interface (Optional)**: Provide remote monitoring and control.

---
