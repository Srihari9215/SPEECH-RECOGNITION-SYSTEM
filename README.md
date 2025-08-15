# SPEECH-RECOGNITION-SYSTEM


COMPANY: CODTECH IT SOLUTIONS

"NAME: SRIHARI A

"INTERN ID: CT04DY35

"DOMAIN: EMBEDDED SYSTEMS"

DURATION: 4 WEEEKS

"MENTOR: VAISHALI"

Project Title:

Speech Recognition System 

🎯 Objective:

To control home appliances (like a bulb or fan) using voice commands sent via an Android smartphone with speech-to-text and Bluetooth capability.

🧠 How It Works:

The Android app captures voice input, converts it to text, and sends it as a command to the Arduino via Bluetooth.

The Arduino receives the serial input and checks for specific commands like:

"Turn on light" or "Turn off fan" etc.

Based on the command, Arduino activates or deactivates relays or outputs to control electrical devices (like the bulb in your circuit).

The user can observe the result through visual indicators like bulbs or motors.

🔌 Hardware Components:

Arduino Uno

HC-05/HC-06 Bluetooth Module

Relay Module or Transistor Driver (not clearly shown, but assumed for high-voltage control)

Light bulb (as output device)

DC fan or motors (as output devices)

9V battery for external power

Android phone with speech-to-text Bluetooth app (e.g., Arduino Voice Control, Bluetooth Terminal, etc.)

Breadboard, resistors, jumper wires

🔁 Voice Control Commands:

Example spoken commands sent via Android (converted to serial text):

Voice Command	Arduino Command Trigger	Action
“Turn on light”	L1ON	Turns bulb ON
“Turn off light”	L1OFF	Turns bulb OFF
“Turn on fan”	FANON	Turns fan ON
“Turn off fan”	FANOFF	Turns fan OFF

Output:
https://github.com/Srihari9215/SPEECH-RECOGNITION-SYSTEM/issues/1#issue-3325198540
