# COMPANY:- CODTECH IT SOLUTION
# NMAE:- SUMIT KUMAR
# INTERN ID:- CT04DF1595
# DOMAIN:- Internet Of Things
# DURATION:- 4 WEEKS
# MENTOR:- NEELA SANTOSH
# DESCRIPTION #
# OUTPUT:-
![Image](https://github.com/user-attachments/assets/7e8dd68f-bccb-49d6-8906-0d2f678e6e7c)
https://github.com/user-attachments/assets/ffb7b182-31f6-49c0-b114-637098577bab
Home Automation Project Using ESP32, Relay Module, and Alexa Integration

Home automation is a growing trend that brings convenience, security, and energy efficiency into our everyday lives. A simple yet powerful home automation project can be built using basic hardware components like the ESP32 microcontroller, 5V relay module, 220V bulb, breadboard, connecting wires, and integrated with Sinric Pro and Amazon Alexa for smart voice-controlled operation.

Project Overview
This project aims to control a 220V household bulb using voice commands or a mobile app, with the help of Alexa and Sinric Pro, a popular IoT platform. The ESP32 serves as the brain of the project, while the 5V relay module acts as an electrical switch that safely controls the 220V bulb. The breadboard and jumper wires allow temporary and flexible circuit connections during prototyping.

Hardware Components
ESP32 Microcontroller: A powerful microcontroller with built-in Wi-Fi and Bluetooth, used to connect the system to the internet and control the relay.

5V Relay Module: Used to switch high-voltage appliances like a 220V bulb. The relay is triggered by a 3.3V or 5V signal from the ESP32.

220V Bulb: The load in this project, controlled via the relay.

Breadboard: Used to prototype the circuit without soldering.

Connecting Wires: Jumper wires are used to connect all components on the breadboard.

Software Components
Sinric Pro: A cloud-based IoT platform that connects smart devices to Alexa and Google Home. It provides APIs and device control via mobile app or voice.

Amazon Alexa: Acts as the voice interface. You can turn the bulb ON or OFF with simple voice commands like “Alexa, turn on the light.”

Arduino IDE: Used to write and upload code to the ESP32.

Working Principle
The ESP32 connects to your Wi-Fi network and registers itself on Sinric Pro using an API key and device ID.

A 5V relay is connected to one of the digital output pins of the ESP32. The relay’s input pin (IN) receives a HIGH or LOW signal to switch the bulb ON or OFF.

When a voice command is given to Alexa, it sends the request to the Sinric Pro cloud server, which then communicates with the ESP32 over the internet.

The ESP32 receives the signal and activates or deactivates the relay accordingly, controlling the 220V bulb.

Advantages
Voice-Controlled Automation: Easily turn devices on/off using voice with Alexa.

Remote Access: Control appliances from anywhere in the world using the Sinric Pro app.

Cost-Effective: Uses easily available and low-cost components.

Scalable: More devices can be added and controlled using the same setup.

Conclusion
This home automation project is an excellent example of combining low-cost hardware with modern IoT platforms. With ESP32 at the core, and the integration of Sinric Pro and Alexa, users can enjoy the convenience of controlling home appliances with just their voice or a smartphone. It serves as a perfect entry point for beginners into the world of IoT and smart home technology.

