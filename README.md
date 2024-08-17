# raspbery-pico-w-codes-     
### **Repository Description**

This repository contains a MicroPython script for the Raspberry Pi Pico W that reads temperature and humidity data from a DHT22 sensor and publishes it to Adafruit IO using MQTT.

#### **Features**
- **Wi-Fi Connectivity**: Connects to a Wi-Fi network using provided credentials.
- **DHT22 Sensor Integration**: Measures temperature and humidity.
- **Adafruit IO Integration**: Publishes sensor data to Adafruit IO feeds for temperature and humidity.
- **Error Handling**: Includes basic error handling for sensor read and data publishing failures.

#### **Setup Instructions**
1. **Configure Wi-Fi**: Update `ssid` and `password` with your network credentials.
2. **Adafruit IO Credentials**: Replace `AIO_USERNAME` and `AIO_KEY` with your Adafruit IO account details.
3. **Run Script**: Upload and run the script on your Raspberry Pi Pico W.

#### **Usage**
- **Temperature and Humidity**: The script reads values from the DHT22 sensor, converts them to Celsius and percentage, and publishes them to Adafruit IO.
- **Logging**: Outputs temperature and humidity readings to the shell and logs publishing status.

#### **Dependencies**
- `dht` (DHT sensor library)
- `umqtt.simple` (MQTT client library)
- `network` (Network management)

**Note**: Ensure you have installed the necessary MicroPython libraries for the script to run correctly.
