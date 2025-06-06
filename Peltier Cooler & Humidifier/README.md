---

## Project: ESP32 Peltier Cooler & Humidifier

This project explores thermoelectric cooling and humidity manipulation using an ESP32. A Peltier module's cold side will be used to condense ambient humidity, collecting water in a small reservoir. The waste heat from the Peltier's hot side will then be used to gently warm this collected water, aiding in its evaporation and thus humidifying the surrounding air. The system will monitor temperatures and humidity, and potentially explore calculations related to the latent heat of condensation and vaporization.

### Key Learning Outcomes:

*   **Thermoelectric Principles**: Understanding how Peltier modules work for cooling and heating.
*   **Heat Transfer & Condensation**: Exploring concepts of dew point, condensation, and heat dissipation.
*   **Water State Transitions**: Calculating or estimating energy involved in phase changes of water (condensation and evaporation).
*   **Sensor Integration**: Using temperature (e.g., DS18B20, thermistors) and humidity sensors (e.g., DHT22, SHT31).
*   **Power Management**: Controlling a relatively high-power device like a Peltier module with an ESP32 (likely via a MOSFET or relay).
*   **System Design**: Integrating cooling, water collection, and warming/humidification components.
*   **Data Logging & Display**: Showing temperatures, humidity, and potentially energy calculations on an OLED display or web interface.

### Peripherals (Conceptual):

*   ESP32 Dev Board
*   Peltier Module (e.g., TEC1-12706)
*   Heatsink and Fan for Peltier Hot Side
*   Cold Side Heatsink/Condensation Surface
*   Temperature Sensors (for hot side, cold side, ambient, water reservoir)
*   Humidity Sensor (for ambient air and potentially near the humidifier output)
*   Small Water Reservoir
*   MOSFET or Relay Module for Peltier control
*   OLED Display (e.g., 0.96" I2C)
*   Power Supply suitable for Peltier module and ESP32
*   Micro-USB Cable
*   Breadboard & Jumper Wires
*   Custom 3D-printed enclosure for airflow management, water collection, and component housing.

### Core Functions:

*   **Peltier Control**: Activate and deactivate the Peltier module based on setpoints or timers.
*   **Temperature Monitoring**: Measure temperatures at critical points (Peltier hot/cold sides, ambient, reservoir).
*   **Humidity Monitoring**: Measure ambient relative humidity.
*   **Water Collection**: Design a surface on the Peltier cold side to efficiently condense and collect water.
*   **Humidification**: Utilize waste heat from the Peltier's hot side to warm the collected water and promote evaporation.
*   **Energy Calculation (Optional)**: Estimate the energy transferred during condensation and required for vaporization based on collected water volume and temperature changes.
*   **Local Display**: Show current temperatures, humidity, and system status on the OLED screen.
*   **Web Interface (Optional)**: Provide a web dashboard for remote monitoring and control.

---
