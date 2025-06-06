---

## Project: ESP32 Advanced Environmental Monitoring Station

Build a sophisticated indoor air quality station with this kit! You'll learn to use an ESP32 to monitor crucial environmental factors like Carbon Dioxide (CO2), temperature, humidity, and ambient light. This project emphasizes data collection, local display, and creating a web dashboard for real-time and historical insights into your environment.

### Key Learning Outcomes:

* **Multi-Sensor Integration*: Connecting and reading data from various environmental sensors (CO2, DHT, LDR).
* **Serial & I2C Communication*: Interfacing with different sensor types using appropriate communication protocols.
* **Data Interpretation*: Converting raw sensor readings into meaningful metrics (ppm, degrees, percentage).
* **Data Logging & Visualization*: Collecting and storing environmental data, then displaying it both locally on an OLED screen and remotely via a custom web dashboard.
* **Web Server Development*: Creating a functional web interface on the ESP32 to serve real-time data and historical trends.
* **Environmental Awareness*: Gaining a deeper understanding of indoor air quality and its impact.

### Peripherals Included:

* ESP32 Dev Board
* MH-Z19B CO2 Sensor Module
* DHT11 or DHT22 Temperature & Humidity Sensor
* LDR (Light Dependent Resistor) & 10k Ohm Resistor
* 0.96" I2C OLED Display (128x64 pixels)
* Micro-USB Cable
* Breadboard & Jumper Wires
* Custom 3D-printed Enclosure/Station Housing (designed for sensor placement)

### Core Functions:

* **CO2 Sensing*: Continuously monitor Carbon Dioxide levels in parts per million (ppm).
* **Temperature & Humidity*: Periodically read ambient temperature (in °C and °F) and relative humidity (in ).
* **Light Intensity*: Measure ambient light levels.
* **Local Display*: Show all real-time environmental data on the OLED screen, cycling through different metrics.
* **Web Dashboard*: Host a local web server on the ESP32 to display live and historical environmental data with basic charts.
* **Serial Output*: Print all sensor data to the Serial Monitor for detailed analysis.

---