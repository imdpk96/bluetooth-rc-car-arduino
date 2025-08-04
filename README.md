# bluetooth-rc-car-arduino
DIY Bluetooth Controlled RC Car using Arduino UNO, L293D Motor Driver, and HC-05 Bluetooth module. Control your car with a mobile app via Bluetooth. Complete code, circuit diagram, and app included.

# 🚗 Bluetooth Controlled RC Car using Arduino | Full DIY Guide

Welcome to this fun and beginner-friendly project! In this repository, you'll learn how to make a Bluetooth-controlled RC car using an **Arduino UNO**, **L293D Motor Driver Shield**, and an **HC-05 Bluetooth module**.

This car can be controlled completely wirelessly using your **Android mobile phone** via a free Bluetooth app. Whether you're a student, hobbyist, or robotics enthusiast — this project is simple, educational, and exciting to build.

---

## 📦 What You’ll Find in This Repo

- ✅ **Arduino Code** to control the car motors based on Bluetooth commands  
- ✅ **Mobile App (APK)** to control the car with your phone  
- ✅ **Circuit Diagram** to understand all wiring and connections  
- ✅ Step-by-step **wiring guide** inside this README

---

## 🔧 Components Used

| Component                     | Buy Link |
|------------------------------|----------|
| Arduino UNO                  | [Amazon](https://amzn.to/4mk97sM) |
| L293D Motor Driver Shield     | [Amazon](https://amzn.to/3Uxr3EN) |
| HC-05 Bluetooth Module        | [Amazon](https://amzn.to/4fFG7df) |
| 4× DC Motors with Wheels      | [Amazon](https://amzn.to/4l8wLrv) |
| 12V Battery + Holder          | [Amazon](https://amzn.to/3ISX5bI) |
| Jumper Wires                  | [Amazon](https://amzn.to/41iDec8) |

> ✅ These are affiliate links — using them supports the creator at no extra cost to you.

---

## 📲 Mobile App Control

You can use the provided Android APK (`Bluetooth_RC_Controller.apk`) or any Bluetooth terminal app.

### Bluetooth Commands:
- `F` → Forward  
- `B` → Backward  
- `L` → Left  
- `R` → Right  
- `S` → Stop

---

## 🔌 Circuit & Wiring Guide

### 📍 Motors:
- 2 motors → connect to M1 & M2 terminals on the L293D shield  
- 2 motors → connect to M3 & M4 terminals

### 📍 HC-05 Bluetooth Module:
- VCC → 5V on motor shield  
- GND → GND  
- TX → RX (Arduino Pin 0)  
- RX ← TX (Arduino Pin 1) ⚠️ *(Use a voltage divider: 1kΩ + 2kΩ)*

### 📍 Power:
- 12V battery → connected to shield input terminals (via switch)  
- L293D shield powers both Arduino and the motors

✅ Make sure all GNDs are connected properly (common ground)

---

## 📁 Project Folder Structure


---

## 🎓 Ideal For

- B.Tech / Diploma projects  
- Arduino & robotics beginners  
- Science exhibitions & tech fests  
- Hobby electronics

---

## 👨‍💻 Created By

**Deepak Kumawat**  
🎓 M.Tech (Machine Design), IIT Kharagpur

🌐 Connect with me:  
- 🔗 [LinkedIn](https://linkedin.com/in/imdpk96)  
- 📸 [Instagram](https://instagram.com/imdpk96)  
- 💻 [GitHub](https://github.com/imdpk96)  
- 🧪 [Tinkercad](https://www.tinkercad.com/users/eWTnVR7FKkS-dpk-kmwt)  
- 🎥 [YouTube – The IITian DPK](https://www.youtube.com/@TheIITianDpk)

---

## 🙏 Support

If this project helped you, please:
- ⭐ Star this repo  
- 📢 Share with friends  
- 📬 Message me for questions or improvements

---

**Enjoy building your own RC Car!** 🔧✨
