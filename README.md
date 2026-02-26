# Hey, I'm Hridhik 👋

Systems builder. I like making things that actually fly, scale, and work in the real world.

---

## 🚁 Featured Project — ADDC Aroha

**Autonomous precision-landing drone** built for the Autonomous Drone Delivery Challenge (ADDC).

> GPS mission → YOLOv8 marker detection → vision-based precision landing. All running on a Raspberry Pi 5 with a Hailo-8L AI accelerator.

| Layer | Stack |
|-------|-------|
| Flight Controller | Cube Orange (ArduPilot / PX4) |
| Companion Computer | Raspberry Pi 5 |
| AI Accelerator | Hailo-8L (13 TOPS) |
| AI Model | Custom YOLOv8 compiled to `.hef` |
| Comms | MAVLink UDP · MAVSDK · ZMQ |
| Control Loop | 20 Hz offboard P-controller (normalised X/Y error) |

Three development phases: x86 SITL → RPi5 HITL with Hailo → real-world flight.

👉 **[hridhik-ad/addc_aroha](https://github.com/hridhik-ad/addc_aroha)**

---

## 🛠 Tech Stack

```
Python · FastAPI · MongoDB
Linux · Raspberry Pi 5
PX4 / ArduPilot · MAVSDK · MAVLink
YOLOv8 · Hailo-8L (NPU)
React · Flutter
MATLAB
```

---

## 📌 Other Projects

| Project | What it is |
|---------|-----------|
| Micro-Expressions Detector | MATLAB computer-vision college project |
| FastAPI backends | Learning API design, working towards AI-automated services |

---

## 📫 Find me

- GitHub: [@hridhik-ad](https://github.com/hridhik-ad)

---

*Always building. Currently making drones land where they're supposed to.*
