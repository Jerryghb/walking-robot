# Multi-Legged Walking Robot (Theo Jansen Mechanism)

![Project Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Course](https://img.shields.io/badge/Course-MANU2518%20Advanced%20Manufacturing%20and%20Mechatronics-blue)

<!-- 📸 Hero Image Placeholder: Upload your best full-body photo of the final robot here -->
<img width="870" height="863" alt="image" src="https://github.com/user-attachments/assets/621f60a4-4ce3-4fd9-9f4c-be4962abc448" />

## 📖 Project Background

This project focuses on the design and fabrication of a bio-inspired multi-legged walking robot using the **Theo Jansen linkage mechanism**. The core objective of this robot is to demonstrate how simple linkage systems can be used for practical tasks, specifically by maintaining stable locomotion while carrying a payload (approximately 200g - 220g, equivalent to a small milk bottle) across different surfaces. 

Unlike wheeled robots that rely on rolling, the Jansen mechanism translates continuous rotary motion into a stepping action, allowing for efficient movement on uneven surfaces.

## ✨ Key Features

* **Bio-Inspired Locomotion:** Utilises a one-degree-of-freedom Jansen linkage system (eight rigid links and seven revolute joints per leg) to simulate an animal's step cycle.
* **Lightweight & Robust Body:** The primary structural components are laser-cut from 3mm acrylic plates, providing an optimal balance of strength and low weight (approx. 250g total weight).
* **Custom Payload Carrier:** Features a specially designed 3D-printed payload tray to securely hold a 180ml - 220ml milk box during operation.
* **Upgraded Joint Mechanisms:** Replaces standard screw joints with custom shaft locks for smoother, jam-free rotation.
* **Power & Actuation:** Driven by a single DC motor powered by a compact 9V battery.

## 🛠️ Fabrication & Hardware

* **Chassis & Legs:** 3mm transparent acrylic sheets (Laser-cut).
* **Payload Holder & Shafts:** 3D printed custom components.
* **Fasteners:** Inward-oriented screws and shaft locks for a snag-free, clean profile.
* **Power Source:** 9V Battery.
* **Actuator:** Standard DC Motor.

* Laser Cutting Design
<img width="1256" height="916" alt="image" src="https://github.com/user-attachments/assets/56ce7a67-9b93-47bf-8e27-467a981f31c8" />
<img width="811" height="386" alt="image" src="https://github.com/user-attachments/assets/3f7ca7c4-0c2e-42c3-869a-3a9f5917dd63" />

* 3D Printed Holder
<img width="694" height="578" alt="image" src="https://github.com/user-attachments/assets/64f5a99c-4898-4828-bae9-b12e39f39e73" />
<img width="643" height="581" alt="image" src="https://github.com/user-attachments/assets/c35c19c3-2858-49eb-9fd2-6002b3b82489" />


## 🚀 Development Process & Iterations

The final robot is the result of continuous testing and iteration:

1. **First Prototype:** Built at 2x scale. Proved too heavy and required excessive torque for the initial 3V (2x AA) power source.
   <img width="1144" height="780" alt="image" src="https://github.com/user-attachments/assets/890a5961-3b6c-4b9f-a319-ea78a3749493" />


2. **Second Prototype:** Scaled down to the original dimensions. Revealed weaknesses in joint stability (loose screws) and leg flimsiness (single thin triangular pieces).
   <img width="1144" height="780" alt="image" src="https://github.com/user-attachments/assets/a9018353-97a7-400d-872b-93d53330eac7" />
   <img width="280" height="812" alt="image" src="https://github.com/user-attachments/assets/0d9e8fca-e677-4561-b03b-5b6726a64494" />
   <img width="874" height="793" alt="image" src="https://github.com/user-attachments/assets/fd48b920-3f9a-4221-b6d8-81901bf01662" />

3. **Final Product:** * Upgraded to a **9V battery** for sufficient motor torque.
    * Reinforced each leg with **dual triangular pieces** for enhanced lateral stability.
    * Integrated **shaft locks** instead of loose screw joints for smooth rotation.
    * Added the **3D-printed payload holder**.

   <img width="828" height="719" alt="image" src="https://github.com/user-attachments/assets/8275b6fd-5471-4f8e-922e-652cb7396bac" />


## 📊 Testing and Evaluation

* **Payload Capacity:** Successfully carries a 180ml milk box payload while in motion.
* **Locomotion:** Walks perfectly straight on flat, smooth surfaces. Displays a slight turning deviation on rougher terrain (e.g., carpet) before stabilizing forward movement.
* **Weight:** ~250 grams (including battery and motor).

## 👥 Team Contributors

* **Cù Đình Bách** - Project Leader / Body Design / Documentation
* **Trần Quốc Việt Hải** - Leg Design / Documentation
* **Cao Phương Linh** - Item Holder & Connector Design / Documentation
* **Nguyễn Minh Anh** - Assembly & Testing / Documentation

The project was conducted at RMIT University Vietnam with fellow university students.

## 📚 References

1. wolfCat workshop, “Paper Linkages Part 6 - Jansen’s Linkage,” *Youtube*. [Link](https://www.youtube.com/shorts/PBuOBGfEzXk)
2. Wikipedia Contributors, “Jansen’s linkage,” *Wikipedia*. [Link](https://en.wikipedia.org/wiki/Jansen%27s_linkage)
3. Rohit John Varghese, “Stair-Ascending Strandbeest,” *The University of Texas at Austin*. [Link](https://cloud.wikis.utexas.edu/wiki/spaces/RMD/pages/51054238/10+-+Stair-Ascending+Strandbeest)
