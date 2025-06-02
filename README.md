# push-button-counter

NAME: RANGA DEEPSHIKA

COMPANY: CODTECH IT SOLUTIONS

INTERN ID: CT04DM585

DOMAIN: EMBEDDED SYSTEMS

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH


The Push Button Counter project in Wokwi is a beginner-friendly digital electronics simulation that demonstrates how a microcontroller can be used to implement a simple counting system based on user input. In this project, a push button is connected to an Arduino Uno (or similar microcontroller) to increment a 4-bit binary counter. The current value of the counter is displayed either through four LEDs or on the Serial Monitor, offering a clear, visual representation of how digital logic and binary counting work. This project not only teaches basic digital design concepts such as input handling and binary output but also introduces important programming concepts like debouncing, state detection, and bit manipulation. In this setup, each button press is detected using digital input pins, and the count is stored in an integer variable which loops from 0 to 15 (4-bit range). Debouncing is handled through a software delay or logic to ensure only one count is registered per press, avoiding multiple triggers due to the mechanical noise of the button. LEDs are connected to four digital output pins of the Arduino, and bitwise operations are used to extract and display each bit of the current count value, which helps in understanding how binary data is interpreted and output in embedded systems. The project begins by initializing the I/O pins in the Arduino sketch, assigning digital pins for the push button and the LEDs. In the main loop, the program continuously reads the button's state and compares it with the previous state to detect a transition from HIGH to LOW, indicating a valid button press. Upon detection, the counter is incremented and the result is either printed to the Serial Monitor or sent to the LEDs for binary display. A delay is added to prevent button bounce from causing erroneous multiple increments. The Wokwi simulator provides a visual environment where users can easily drag and connect components like push buttons, LEDs, and Arduino boards. This eliminates the need for physical hardware, making the project ideal for remote learning, experimentation, or early-stage prototyping. For advanced users, the project can be extended by adding a second button to decrement the counter, implementing interrupt-based input handling for more accurate response, or using a 7-segment display instead of LEDs for more user-friendly decimal output. This project reinforces foundational knowledge in digital electronics, including the binary number system, microcontroller programming, and circuit simulation, making it perfect for students and hobbyists. Additionally, it fosters logical thinking and problem-solving skills, as users must ensure proper timing, avoid overflow, and manage input/output effectively. The Push Button Counter in Wokwi is not just a technical exercise but a practical gateway into the world of embedded systems, giving users a tangible sense of control over hardware through software. Whether used in an educational setting or as a personal learning project, it provides a solid base to explore more complex systems involving sensors, displays, or serial communication in future projects. Ultimately, it is a simple yet powerful way to understand the intersection of electronics and programming in an interactive and visually rewarding format.

#OUTPUT SIMULATION

![Image](https://github.com/user-attachments/assets/b95c25e4-5c59-4534-be2f-6cc7c0d0724f)
