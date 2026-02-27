# Hey, I'm Hridhik 👋

**Systems Builder & Explorer.** I thrive at the intersection of hardware and high-performance software—building systems that fly, scale, and solve real-world bottlenecks.

---

### 🚁 Featured Project — [ADDC Aroha](https://github.com/hridhik-ad/addc_aroha)
**Autonomous Precision-Landing System** built for the Autonomous Drone Delivery Challenge (ADDC).

> This project was about closing the loop between computer vision and flight dynamics. I engineered a pipeline that takes a drone from a GPS mission to a sub-meter precision landing using real-time AI inference at the edge.

| Layer | The Stack |
| :--- | :--- |
| **Flight Brain** | Cube Orange (ArduPilot / PX4) |
| **Edge Compute** | Raspberry Pi 5 + **Hailo-8L (13 TOPS)** |
| **Vision Core** | Custom YOLOv8 compiled to `.hef` |
| **Communication** | MAVLink UDP · MAVSDK · ZMQ |
| **Control Logic** | 20 Hz Offboard P-controller (Normalised X/Y Error) |

**The Workflow:** Moved from **x86 SITL** (Simulation) to **RPi5 HITL** (Hardware-in-the-loop) with NPU acceleration, finally validating the stack in **real-world flight**.

---

### ⚽ Featured Project — [Turfez](#)
**Full-stack Turf Booking Ecosystem.** Built a streamlined platform for sports enthusiasts to book local turfs. This was my deep dive into building **scalable systems** that handle real users and real-time availability.

* **Backend:** High-concurrency API built with **FastAPI**.
* **Database:** Flexible data modeling using **MongoDB**.
* **Frontend:** Cross-platform mobile experience via **Flutter**.

---

### 🛠 Tech Stack & Curiosity

I don’t just use tools; I learn how they work from the ground up—from **Micrograd** to building **Raw DNS Forgers**.

* **Languages & Frameworks:** Python (FastAPI), React, Flutter, MATLAB.
* **Robotics & Edge AI:** PX4 / ArduPilot, MAVSDK, YOLOv8, Hailo-8L NPU.
* **Infra & Systems:** Linux (Raspberry Pi/Server), MongoDB, ZMQ, MAVLink.
* **Currently Exploring:** MLOps, System Design patterns, and AI-automated services.

---

### 📌 Philosophy

I'm a **first-principles learner**. Whether it's optimizing a 13 TOPS AI accelerator or architecting a backend, I’m driven by a relentless curiosity for how complex systems stay upright and scale in production environments.

---

### 📫 Let's Connect

* **GitHub:** [@hridhik-ad](https://github.com/hridhik-ad)

*Building the future, one control loop at a time.*
