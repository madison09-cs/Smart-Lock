# 🔐 Smart Lock with Serial Monitor

A simple yet powerful Arduino-based **smart lock system** that mimics the functionality of modern digital door locks. Controlled through the **Serial Monitor**, this project uses a **micro servo motor** to simulate locking/unlocking and an **RGB LED** to visually indicate the lock status.

---

## 📝 Description

**Smart Lock** is an Arduino project designed to replicate how smart door locking systems function in today's technology-driven homes and offices. Using the **Serial Monitor**, the user can send commands to lock or unlock a virtual door. A **micro servo motor** handles the mechanical movement, while an **RGB LED** indicates whether the door is locked (red) or unlocked (green).

This project introduces core concepts like:
- Serial communication
- Servo motor control
- Status feedback using RGB LEDs

---

## 🔧 Components Used

| Component             | Quantity |
|-----------------------|----------|
| Arduino Uno R3        | 1        |
| Breadboard            | 1        |
| Micro Servo Motor     | 1        |
| RGB LED (Common Cathode) | 1     |
| Jumper Wires / Cables | Several  |
| USB Cable (for Arduino IDE) | 1   |

---

## 🚀 Installation & Setup

1. **Wiring Setup**:
   - **Micro Servo**:
     - Signal (orange/yellow) → Digital Pin 9
     - VCC (red) → 5V
     - GND (brown/black) → GND
   - **RGB LED**:
     - Red → Digital Pin 3
     - Green → Digital Pin 5
     - Blue → (optional or unused)
     - Common cathode → GND

2. **Upload Code**:
   - Open the Arduino IDE.
   - Connect your Arduino Uno via USB.
   - Write or paste your sketch.
   - Select the correct **board** and **COM port**.
   - Upload the code to your board.

3. **Using Serial Monitor**:
   - Open Serial Monitor (baud rate: **9600**).
   - Type one of the following commands and press enter:
     - `lock` → Locks the door (servo turns, LED red)
     - `unlock` → Unlocks the door (servo turns, LED green)

---

## ⚙️ How It Works

1. The Arduino listens for input through the **Serial Monitor**.
2. When the user types `lock`, the servo rotates to the locked position (e.g., 0°), and the RGB LED turns red.
3. When the user types `unlock`, the servo rotates to the unlocked position (e.g., 90° or 180°), and the RGB LED turns green.
4. This basic feedback system simulates how smart locks visually and physically respond to remote input.

---

## 💼 Portfolio

Explore more of my projects and engineering work here:  
🔗 [My Portfolio](https://sites.google.com/d/1kRYFgoPpI5KiRHlfU4u9C--i8z4OA6I5/p/1_ZLDAirpPNf5aijgyz-LQdDFrC5D1Gd2/edit)

---

## 🔬 Simulation

You can view and interact with this project virtually via Tinkercad:  
▶️ [Tinkercad - Smart Lock Simulation](https://www.tinkercad.com/things/8Jw8grInGkO-copy-of-face-recognition-smart-lock)

---

## 🙌 Credits

- Created by **[Madison Diggs]**
- Powered by **Arduino Uno R3**
- Inspired by modern IoT smart door locking systems

---

## 📄 License

This project is licensed under the Code in the Schools.

---
