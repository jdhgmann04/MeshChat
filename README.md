MQTT Chat Application
This is a simple MQTT chat application built with Python, using the tkinter library for the graphical user interface and the Paho MQTT library for communication with an MQTT broker.

Features
Connect to an MQTT broker with a specified address, port, topic, username, and password.
Display connection status.
Receive and display messages from the MQTT broker.
Send messages to the MQTT broker.

Requirements
Python 3
Paho MQTT library: pip install paho-mqtt
tkinter (usually included with Python 3)

How to Run
Clone or download this repository.
Make sure you have the Paho MQTT library installed.
Run the script in a terminal or command prompt: python mqtt_chat.py
Enter the MQTT broker details, including the address, port, topic, username, and password.
Click the "Connect" button to establish a connection with the MQTT broker.
Once connected, you can send and receive messages in the chat application.

Customization
You can customize the default topic by modifying the topic_var.set() line in the script. Replace the value with your desired topic string:

python
Copy code
topic_var.set("your_desired_topic")

License
This MQTT chat application is open-source and available under the MIT License. Please refer to the LICENSE file for more details.
