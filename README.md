# push-button-counter

NAME: RANGA DEEPSHIKA

COMPANY: CODTECH IT SOLUTIONS

INTERN ID: CT04DM585

DOMAIN: EMBEDDED SYSTEMS

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH


This project is a beginner-friendly embedded systems application that integrates basic user input, environmental sensing, and real-time data display. The project is titled **"Push Button Counter with Temperature Sensor Display on LCD or Serial Monitor"** and is implemented using an **Arduino Uno**, a **DHT11 (or DHT22) temperature sensor**, a **push button**, and a **16x2 LCD display** or the **Arduino Serial Monitor**.

The purpose of this project is two-fold: to allow users to manually count events using a push button, and simultaneously monitor and display the ambient temperature. When the button is pressed, a counter variable is incremented. At the same time, the temperature sensor periodically measures the surrounding temperature. Both values are displayed together, giving the user a simple interactive interface that combines digital input with environmental sensing.

The temperature data is acquired using a **DHT11/DHT22** sensor, which is capable of measuring temperature (and humidity, if needed). The sensor provides temperature data in degrees Celsius and is interfaced with the Arduino using a single digital pin. The data from the sensor is read periodically inside the main loop of the program, ensuring that the display is constantly updated with the latest reading.

For the counting mechanism, a **push button** is connected to a digital pin on the Arduino and configured using internal pull-up resistors. Every time the button is pressed, the program detects a falling edge (transition from HIGH to LOW), increments the count, and introduces a short delay to avoid multiple counts caused by mechanical bouncing (debouncing).

The output of the system is visualized using either a **16x2 LCD display** with an I2C interface or the **Arduino Serial Monitor**. The LCD provides a clear, readable display in real-time and makes the project completely stand-alone. Alternatively, using the Serial Monitor allows for easier debugging and data logging during development. The display shows two lines: the first line for the current temperature (e.g., "Temp: 27.0°C") and the second line for the count (e.g., "Count: 4").

This project is ideal for learning how to:

* Interface sensors and input devices with Arduino.
* Read and debounce digital inputs.
* Display dynamic data using an LCD or Serial Monitor.
* Use libraries such as `DHT.h` for sensor data and `LiquidCrystal_I2C.h` for the LCD.

In terms of real-world applications, this setup can be a prototype for:

* An environmental monitoring system.
* A people or item counter for controlled environments.
* Educational tools to teach sensor integration and display techniques.
* A foundation for building more advanced IoT-based projects.

The project demonstrates how microcontrollers can read physical inputs, process data, and provide human-readable outputs. It’s a stepping stone toward building more complex systems involving multiple sensors and automated feedback.

Overall, this project blends interactivity, sensor interfacing, and display technology into a compact and functional embedded system, perfect for educational demonstrations, small-scale prototypes, and beginner-level IoT applications.

#output

![Image](https://github.com/user-attachments/assets/89c62817-77d0-4134-9bcc-e42c2b056867)

