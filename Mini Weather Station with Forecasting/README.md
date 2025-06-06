---

## Project: ESP32 Mini Weather Station with Data Logging & Forecasting

This project expands on basic weather monitoring by incorporating data logging over time and attempting simple weather trend forecasting. An ESP32 will collect data from temperature, humidity, and barometric pressure sensors. This data will be stored (e.g., on an SD card or ESP32 flash memory) and used to display trends and make rudimentary predictions (e.g., pressure falling rapidly might indicate approaching rain).

### Key Learning Outcomes:

*   **Advanced Sensor Integration**: Using multiple environmental sensors (temperature, humidity, barometric pressure - e.g., BME280/BMP280).
*   **Data Logging**: Storing sensor data with timestamps to internal memory or an SD card.
*   **Data Analysis & Interpretation**: Analyzing trends in pressure, temperature, and humidity.
*   **Basic Forecasting Logic**: Implementing simple algorithms to predict weather changes based on observed trends (e.g., pressure tendency).
*   **Timekeeping**: Using NTP or an RTC for accurate timestamps.
*   **Displaying Data & Trends**: Showing current weather, historical data charts (if possible on OLED, or via web), and forecast icons on an OLED display and/or web interface.
*   **File System Management (if using SD card)**: Reading and writing data to files.

### Peripherals (Conceptual):

*   ESP32 Dev Board
*   BME280 or BMP280 Sensor (Temperature, Humidity, Pressure)
*   Optional: Anemometer (wind speed) and Wind Vane (wind direction) for a more advanced station.
*   Optional: Rain Gauge sensor.
*   MicroSD Card Module and MicroSD Card (for data logging)
*   OLED Display (e.g., 1.3" I2C for more space) or small TFT
*   RTC Module (e.g., DS3231) if offline timekeeping is critical
*   Micro-USB Cable
*   Breadboard & Jumper Wires
*   Custom 3D-printed enclosure for weatherproofing sensors (if placed outdoors) or a neat desk housing.

### Core Functions:

*   **Environmental Sensing**: Regularly read temperature, humidity, and barometric pressure.
*   **Data Logging**: Store timestamped sensor readings to flash memory or SD card.
*   **Trend Analysis**: Calculate changes in pressure over time (e.g., 3-hour pressure tendency).
*   **Simple Forecasting**: Display a weather forecast icon (e.g., sunny, cloudy, rain) based on pressure trends and humidity.
*   **Local Display**: Show current conditions, time, date, and forecast on the OLED screen.
*   **Web Interface (Optional)**: Provide a dashboard to view current data, historical charts, and detailed logs.
*   **Wi-Fi Connectivity**: For NTP time synchronization and web server.

---
