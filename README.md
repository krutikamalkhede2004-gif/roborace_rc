# 🏎️ ARENA RC — ESP32 Racing Robot Controller

A mobile-friendly racing robot controller using:

- 📱 Android phone
- 🔵 Bluetooth Low Energy (BLE)
- 🤖 ESP32
- ⚙️ L298N motor driver
- 🏁 Two DC motors

## 🎮 Features

- Racing-style steering joystick
- Throttle control
- Brake button
- Boost mode
- ESP32 BLE connection
- Arena-inspired interface
- Emergency STOP button
- Mobile-friendly design

## 🔧 Hardware

- ESP32
- L298N motor driver
- 2 DC motors
- Robot chassis
- Battery/power supply

## 📱 How to Use

1. Upload the ESP32 `.ino` code to the ESP32.
2. Connect the motors and L298N motor driver.
3. Open the controller website on an Android phone using Chrome.
4. Tap **CONNECT**.
5. Select the ESP32 BLE device.
6. Use the joystick and throttle to control the robot.

## 🌐 Controller

GitHub Pages:
https://krutikamalkhede2004-gif.github.io/arena-rc/

## 🔵 BLE

The phone communicates with the ESP32 using Bluetooth Low Energy.

The controller sends:

`throttle,steering,brake,boost`

Example:

`50,-20,0,1`

## 🏁 Project

Built as a phone-controlled racing robot for an arena with curves, ramps, slalom sections and obstacles.

**ARENA RC — Build • Drive • Race 🏎️**
