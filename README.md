# Arduino DHT22 Temperature and Humidity Monitor

This project reads temperature and humidity values from a **DHT22 sensor** using an **Arduino Uno** and displays the results on the Serial Monitor.

---

## Components Required
- Arduino Uno
- DHT22 Temperature & Humidity Sensor
- Jumper Wires
- Breadboard (optional)

---

## Circuit Connections
1. **DHT22 VCC** → **5V** on Arduino  
2. **DHT22 GND** → **GND** on Arduino  
3. **DHT22 Data Pin** → **Digital Pin 6** on Arduino  

---

## Code Explanation
- Includes the `dht.h` library for reading data from the DHT22 sensor.
- Reads temperature and humidity every 4 seconds.
- Prints values to the Serial Monitor in °C and %.
