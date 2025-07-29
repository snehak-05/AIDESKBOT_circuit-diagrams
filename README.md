# 🤖 AI DeskBot – Your Interactive Desk Companion
It's a cute table bot me and my teamamtes made under ES&IOT, it is build using Raspberry pi 4 b+ model and is designed to interact through voice input and ouputs, hands gestures and facial expression. It serves as a friedndly companion, health assistant by providing health reminders time-to-time such as when to take breaks and stay hydrated, also it serves as a smart assistant by interacting with voice output and input.

## Features
- Facial expressions
- Moving hands and body gestures
- Voice interaction
- Provides health reminders
- Answer querries
- It senses Touch & Vibrations and react on them
- Cute, compact design with expressive movements

## Tech  stack
### Hardware
- Raspberry Pi 4 b+ model
- LCD Screen (to display expression)
- Touch & Vibration sensor
- Servo Motors (for body and hands movements)
- Servo Motor Driver (to handle Servos)
- PAM8403 amplifier (to amplify the voice output)
- Speaker (for voice output)
- Microphone (for voice input)
### Software
- Python Programming Language
- Raspberry Pi OS

And we 3D Printed all the body parts of Our Robot to make a cute compact design.

## Libraries Used 
- **pyttsx3** - A Python library for offline text-to-speech (TTS) conversion.
- **speech_recognition** - Recognizes speech input from microphones or audio files using multiple engines.
- **busio** -  Handles I2C/SPI/UART communication in CircuitPython for hardware interfacing.
- **adafruit_servokit** - Controls servo motors using Adafruit’s PCA9685 driver in Python.
- **RPi.GPIO** - Allows Raspberry Pi to control and interact with GPIO pins using Python.
- And Some more like: **time, os, openai, multiprocessing, random, board, PIL**

## How It Works
1. It powers on by 3A 5V C-Type charger.
2. Detects touch and reacts with movement + sound.
3. It changes expression according to the touch and vibration sensors input.
4. Hands and body movements changes according to the expression.
5. It provides health reminders after time intervals.
6. It interacts through voice input given by the user.

## Our Learnings
- We learned how the Raspberry Pi works, including its operating system, hardware setup, and how to configure the Python environment on it.
- We explored how to connect and work with various hardware components, understanding their functions and wiring.
- We gained hands-on experience with multiple Python libraries used for speech, servo control, and GPIO interfacing.
- We discovered what 3D printing is, how the process works, and how much time it takes to bring physical parts to life.
- One of the biggest takeaways was realizing how much can be built from zero knowledge with consistent learning and teamwork.

## Challenges Faced
- Initially, we struggled to set up the Raspberry Pi, as we were unfamiliar with the OS and installation process.
- We encountered issues when trying to install certain Python libraries, as Raspberry Pi OS restricted some dependencies.
- To overcome this, we learned how to create and use a virtual environment, which helped us bypass installation errors and continue development smoothly.

## Key Skills We Learned
- Problem-Solving
- Curiosity and Self-Learning
- Teamwork and Collaboration
- Patience and Persistence (especially during hardware/debugging issues)
- Time Management
- Communication (explaining the project clearly)
- Adaptability (working through OS and hardware limitations)
- Creative Thinking (designing gestures, voice features, etc.)

## Conclusion
This project not only strengthened our technical skills in hardware programming and Python automation but also taught us how creativity and curiosity can turn simple components into an interactive and intelligent companion.
