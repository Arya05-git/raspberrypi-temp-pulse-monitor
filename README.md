# raspberrypi-temp-pulse-monitor
A Raspberry Pi-based real-time monitoring system for detecting body temperature and pulse rate using sensors. Built for healthcare and IoT applications.

# Raspberry Pi Temperature and Pulse Monitor

This project uses a Raspberry Pi to monitor human body temperature and heart rate in real time using a temperature sensor (like MLX90614 or LM35) and a pulse sensor. The data can be displayed on the terminal or stored for analysis.

## 🛠 Technologies Used
- Python
- Raspberry Pi GPIO
- Pulse Sensor (e.g., KY-039 or PulseSensor Amped)
- Temperature Sensor (e.g., MLX90614 or LM35)
- Adafruit Library (for some sensors)

## ⚙️ Features
- Real-time temperature and pulse rate monitoring
- Sensor readings via GPIO pins
- Easy-to-read code and modular structure
- Can be expanded with GUI or cloud upload

## 🚀 Setup
```bash
git clone https://github.com/yourusername/raspberrypi-temp-pulse-monitor.git
cd raspberrypi-temp-pulse-monitor
pip install -r requirements.txt
python main.py
