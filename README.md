# 🚁 Flood Assistance Drone  
An **AI-powered autonomous drone** designed for **flood rescue** using **human detection**, powered by **Raspberry Pi 5**, **Pixhawk 2.4.8**, and **Arducam IMX477**.

## 🌟 Features
✔️ **Autonomous Flight** – Controlled by Pixhawk 2.4.8.  
✔️ **AI-based Human Detection** – Detects flood victims using a trained AI model.  
✔️ **Live Video Feed** – Streams real-time footage using Runcam 2-4K.  
✔️ **GPS Navigation** – Uses Ublox GPS for precise tracking.  
✔️ **Battery Monitoring** – Ensures safe return to base.  

---

## 🔧 Hardware Components

| Component         | Model                  | Function |
|------------------|----------------------|----------|
| 🎮 **Flight Controller** | Pixhawk 2.4.8         | Controls drone movement |
| 📷 **Camera**           | Logitech C270       | AI-based human detection |
| 🖥 **Companion Computer** | Raspberry Pi 5      | Runs AI and processing scripts |
| 🎥 **Video Camera**     | Runcam 2-4K           | Provides live video feed |
| 📡 **GPS Module**       | Ublox Neo-7M          | Position tracking |
| 🔋 **Battery**         | LiPo 3S 5600mAh       | Drone power supply |

---

## ⚙️ Installation 

```bash
git clone https://github.com/your-username/Flood-Assistance-Drone.git
cd Flood-Assistance-Drone
bash setup.sh   # Runs an automatic setup script
```

## 🚀 Running the Drone

Start Autonomous Flight
```bash
python3 src/flight_control/autopilot.py
```
Run AI-based Human Detection
```bash
python3 src/ai_model/detect.py
```
