# IoT-DataScience
IoT Electronics and sensors to collect data for Data Science
IoT (Internet of Things)

**Internet of Things** (IoT) is a network of physical objects embedded with sensors, actuators, software, and connectivity that enables them to collect, exchange, and act on data over the internet without requiring constant human intervention. These "smart" devices, ranging from everyday household items like thermostats, lights, and refrigerators to industrial machines, wearables, and city infrastructure, communicate with each other and cloud platforms to monitor environments, automate processes, and provide real-time insights. IoT powers smarter homes, efficient industries, better healthcare, and intelligent cities by turning ordinary objects into data-generating, decision-making entities.

**Data science projects greatly benefit from IoT devices and sensor data by gaining access to continuous, real-time, high-volume, and highly granular data streams from the physical world.** Sensors in IoT devices (temperature, humidity, motion, GPS, accelerometers, air quality, etc.) generate massive datasets that capture real-world patterns, behaviors, and environmental conditions over time. This rich data enables data scientists to build more accurate predictive models, detect anomalies, optimize processes, and uncover hidden insights through machine learning, time-series analysis, and statistical modeling. For example, IoT data allows for predictive maintenance in manufacturing, personalized health monitoring, energy consumption optimization in smart buildings, and urban traffic forecasting — all with higher precision and timeliness than traditional data sources. The combination of IoT’s scale, variety, and velocity of data significantly accelerates feature engineering, model training, and real-world validation of data science solutions.

Devices families:
- Arduino: 
An open-source electronics platform based on easy-to-use hardware and software. It's widely popular among hobbyists, students, and engineers for prototyping interactive projects, from simple LED blinkers to complex robotics and automation systems.
- ESP32: 
A powerful, low-cost microcontroller developed by Espressif Systems. It features built-in Wi-Fi and Bluetooth, making it ideal for IoT (Internet of Things) applications, wireless sensors, and connected devices. Highly programmable and energy-efficient.
- M5Stack: 
A modular, stackable IoT development platform built around the ESP32. It offers plug-and-play sensors, displays, and accessories in a compact, Lego-like form factor—great for rapid prototyping, education, and portable gadgets.
- Smartphone: 
A handheld computing device that combines mobile phone capabilities with powerful computer-like features. Modern smartphones include high-resolution touchscreens, advanced cameras, app ecosystems, internet connectivity, and sensors for everything from communication to augmented reality.
- Flipper Zero: 
A compact, portable multi-tool for hardware enthusiasts, security researchers, and pentesters. It can interact with RFID/NFC cards, infrared devices, sub-GHz radio signals, iButton, and more—often described as a "Swiss Army knife" for digital and physical security testing.
- BBC Micro
A series of microcomputers designed by Acorn Computers and released in 1981 as part of the BBC Computer Literacy Project in the UK. Famous for its role in education, it introduced a generation to programming (especially BBC BASIC) and influenced the development of ARM processors.
- Raspberry Pi: It is a compact, credit-card-sized single-board computer developed in the UK to promote computer science education. It runs a full Linux operating system and offers impressive computing power for its size, making it extremely popular for DIY projects, IoT, home automation, media centers, robotics, and even edge AI applications.

---

**Here is a list of the most common/typical sensors and actuators for each device:**

### **Arduino**
**Sensors (common):**  
- Temperature/Humidity (DHT11/DHT22)  
- Ultrasonic distance  
- PIR motion  
- Photoresistor (light)  
- Soil moisture  
- Potentiometer  
- Touch / Capacitive  

**Actuators (common):**  
- Servo motors  
- DC motors + drivers  
- LEDs / RGB LEDs  
- Buzzers / Speakers  
- Relays  
- LCD/OLED displays  

### **ESP32**
**Built-in / Common Sensors:**  
- Touch sensors (capacitive pins)  
- Hall effect sensor  
- Temperature sensor (internal)  
- Wi-Fi / Bluetooth signal strength  

**Common External:**  
- Same as Arduino + cameras (OV2640), microphones, IMU (accelerometer/gyro)  

**Actuators:**  
- Same as Arduino (motors, LEDs, buzzers, relays)  
- Neopixel/Addressable LEDs  

### **M5Stack**
**Built-in Sensors (varies by model, e.g. Core2/Basic):**  
- IMU (6-axis accelerometer + gyro)  
- Microphone  
- Button / Touch screen  
- Battery voltage sensor  
- RTC (Real Time Clock)  

**Common Add-on Sensors:**  
- Environment (temp, humidity, pressure, air quality)  
- Light / Color  
- RFID / NFC  
- GPS  

**Actuators:**  
- Vibration motor  
- Speaker  
- RGB LEDs  
- Servo / Motor ports  
- Display (LCD/TFT)  

### **Smartphone**
**Sensors (typical modern phones):**  
- Accelerometer  
- Gyroscope  
- Magnetometer (compass)  
- Proximity sensor  
- Ambient light sensor  
- GPS / GNSS  
- Barometer (pressure)  
- Fingerprint / Face ID  
- Cameras (multiple) + Microphone  

**Actuators:**  
- Vibration motor (haptic)  
- Speaker(s)  
- Display (touchscreen)  
- Flash LED  

### **Flipper Zero**
**Built-in Modules / Sensors-Peripherals:**  
- 125 kHz RFID reader/writer  
- NFC (13.56 MHz) reader/writer  
- Sub-GHz radio (300-928 MHz)  
- Infrared transmitter/receiver  
- iButton reader  
- GPIO pins  
- 1-Wire support  

**Actuators / Outputs:**  
- Buzzer / Speaker  
- LED (RGB)  
- Vibration motor  
- LCD screen  

### **BBC Micro (1980s)**
**Built-in / Basic Inputs:**  
- Keyboard  
- Analogue inputs (4 channels, 12-bit)  
- Cassette tape interface  

**Common Actuators / Outputs:**  
- Speaker (simple sound)  
- Video output (to monitor/TV)  
- Printer port  
- Expansion bus (for motors, lights, etc.)

### **Raspberry Pi**

**Sensors (common):**  
- Camera modules (official Pi Camera)  
- DHT11/DHT22 (temperature & humidity)  
- BMP180/BME280 (pressure & temperature)  
- PIR motion sensor  
- Ultrasonic distance sensor  
- Soil moisture sensor  
- MQ series gas sensors  
- IMU (accelerometer + gyro)  
- GPS modules  
- Touch sensors  

**Actuators (common):**  
- Servo motors & DC motors  
- Stepper motors  
- LEDs & NeoPixel/WS2812 RGB strips  
- Relays (for high-power devices)  
- Buzzers / Speakers  
- LCD / OLED / Touchscreen displays  
- Cooling fans  
- Robotic arms & chassis  

**Key Advantages:** GPIO pins for easy hardware interfacing, support for multiple programming languages (Python is the most popular), built-in Wi-Fi/Bluetooth on newer models (Pi 3, 4, 5), and a powerful CPU/GPU for running complex software, computer vision, and machine learning models directly on the device.

Books:

<img width="309" height="466" alt="image" src="https://github.com/user-attachments/assets/5ba14618-ddc5-47e8-8192-18d64c3d2d8c" />
<img width="323" height="385" alt="image" src="https://github.com/user-attachments/assets/cd7cd6e1-66e3-4d0b-b2cd-c517a740fa6d" />

References

- https://m5stack.com/
- https://www.arduino.cc/
- https://www.raspberrypi.org/
