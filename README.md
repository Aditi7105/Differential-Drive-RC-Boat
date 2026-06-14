# Differential-Drive-RC-Boat

A wireless remote-controlled boat powered by dual DC motors and controlled using a FlySky FS-i6X radio control system. The project utilizes a dual-channel ESC to implement differential steering, allowing smooth navigation and maneuverability on water.

---

## 🚤 Project Overview

This project demonstrates the design and implementation of a Differential Drive RC Boat using:

* FlySky FS-i6X Transmitter and Receiver
* Dual-Channel 4A ESC
* Two DC Motors
* Li-Po Battery

The boat achieves forward, reverse, and turning motions through independent control of the left and right motors.

---

## 📌 Features

* Wireless remote control operation
* Differential drive steering mechanism
* Forward and reverse movement
* Left and right turning capability
* Dual motor propulsion system
* Compact and lightweight design
* Easy to assemble and maintain

---

## 🛠 Hardware Components

| Component                 | Quantity    |
| ------------------------- | ----------- |
| FlySky FS-i6X Transmitter | 1           |
| FlySky Receiver           | 1           |
| Dual Channel 4A ESC       | 1           |
| DC Motors                 | 2           |
| Propellers                | 2           |
| 7.4V Li-Po Battery        | 1           |
| Boat Hull                 | 1           |
| Connecting Wires          | As Required |

---

## ⚙️ System Architecture

```text
FlySky FS-i6X Transmitter
            │
            ▼
     FlySky Receiver
            │
            ▼
    Dual Channel ESC
        │       │
        ▼       ▼
    Motor 1   Motor 2
            │
            ▼
      Boat Propulsion
```

---

## 🔌 Circuit Diagram

The complete circuit diagram is available below:

![Circuit Diagram](circuit_diagram.png)

---

## 🚀 Working Principle

1. The FlySky transmitter sends wireless control signals.
2. The receiver mounted inside the boat receives these commands.
3. The dual-channel ESC processes the received signals.
4. The ESC independently controls both DC motors.
5. Equal motor speeds result in straight-line movement.
6. Speed variation between motors enables turning.
7. Reversing both motors allows backward motion.

---

## 🎮 Boat Movements

### Forward

* Left Motor → Forward
* Right Motor → Forward

### Reverse

* Left Motor → Reverse
* Right Motor → Reverse

### Left Turn

* Left Motor → Slower
* Right Motor → Faster

### Right Turn

* Left Motor → Faster
* Right Motor → Slower

---

## 📊 Results

The RC boat successfully demonstrated:

* Stable wireless communication
* Reliable motor control
* Smooth forward and reverse movement
* Effective differential steering
* Consistent operation on water

---

## 🔮 Future Improvements

* GPS Navigation
* Autonomous Operation
* Obstacle Avoidance
* FPV Camera System
* ESP32 Integration
* LoRa Communication
* ROS2-Based Autonomous Control

---

## 🎯 Applications

* Robotics Education
* Marine Robotics Demonstrations
* Remote-Controlled Water Vehicles
* Embedded Systems Learning
* Hobby and Recreational Projects

---

## 📂 Repository Structure


Differential-Drive-RC-Boat/
│
├── README.md
├── circuit_diagram.png
├── project_report.pdf
├── components_list.md
└── demo_video_link.txt
```

---

## 👩‍💻 Author

**Aditi Chandra**

B.Tech in Robotics and Automation

The Neotia University

National-Level Taekwondo Champion | Robotics Enthusiast | Embedded Systems & ROS2 Learner

---

⭐ If you found this project interesting, consider giving the repository a star.
