# 👁️ ThirdEye – AI-Powered Smart CCTV Safety System

> Transforming Passive CCTV into Proactive Real-Time Crime Prevention 🚨

---

## 📌 Problem Statement & Target Audience

### 🔴 Problem
Over **4.45 lakh crimes against women** are reported annually in India (NCRB 2023).  
Current CCTV systems are **passive** — they record but do NOT react in real-time.  
Police response time is **12–18 minutes**, which is often too late.

### 🎯 Target Audience
- 🏙 Municipal Corporations & Smart Cities  
- 👮 State Police & Safe City Projects (Nirbhaya Fund)  
- 🏬 Malls & Commercial Complexes  
- 🏢 Premium Residential Societies  
- 🚉 Metro Rail Corporations  

---

## 🚀 Our Solution – ThirdEye

ThirdEye turns existing CCTV cameras into **AI-powered safety guardians**.

### 🔥 Features
- ✅ Real-time violence & harassment detection  
- ✅ Scream & abuse detection via audio  
- ✅ Proximity violation detection (<0.5m)  
- ✅ Auto face-blurring for privacy  
- ✅ GPS-tagged 10-sec incident clips  
- ✅ Instant alerts to Police + 1091 helpline  
- ✅ Reassurance SMS to victim  

💡 Works on **existing cameras** (NO new hardware needed)

---

## 🧠 AI Technology Stack

### 🔧 Edge AI
- 📷 **YOLOv8** – Violence detection  
- 🧍‍♂️ **OpenPose** – Body & proximity detection  
- 🎙 **Wav2Vec 2.0** – Audio scream/abuse detection  
- 🎯 **SlowFast** – Gesture violence recognition  
- 📊 **Bayesian Fusion Engine** – Multi-signal decision making  

---

## 🏗 Architecture Flow

CCTV (RTSP) → Jetson Edge AI → Kafka → FastAPI Backend
↓
AI Detection + Fusion
↓
Alert System (Twilio + FCM)
↓
Police + Victim + Dashboard Interface


---

## 🛠 Tech Stack

| Layer | Technology |
|------|------------|
| Edge | Jetson Nano, OpenCV, ONNX |
| AI Models | YOLOv8, OpenPose, SlowFast, Wav2Vec |
| Streaming | RTSP, Kafka |
| Backend | FastAPI, Socket.IO |
| Database | PostgreSQL, MongoDB |
| Cache | Redis |
| Frontend | React.js, Chart.js |
| Alerts | Twilio SMS/Call, Firebase FCM |

---

## ✅ Feasibility & Highlights

✔ Works with **90% existing RTSP/ONVIF cameras**  
✔ < **3 seconds end-to-end alert delay**  
✔ 91% AI Accuracy on Indian dataset  
✔ DPDP Act compliant – Privacy by Design  
✔ Visual-only mode available (for non-audio cameras)  

---

## ⭐ Unique Selling Points (USP)

- 🇮🇳 Trained on **12,000+ India-specific videos**  
- 🔒 **Privacy-first**: Face blur + auto delete (<5 mins)  
- 📩 Sends psychological reassurance SMS to victims  
- 💰 Zero new hardware investment  
- ⚡ Works even in low network areas (Edge AI)

---

## 💼 Business Model

| Tier | Price |
|------|------|
| 1–100 cameras | ₹168/camera/month |
| 101–1000 cameras | ₹150/camera/month |
| Smart City Package | ₹1.5 Lakh/month flat |

🎯 Even **1% market share** = ₹50+ Crore ARR  

---

## 📢 Future Scope
- Crowd incident prediction  
- Audio multilingual abuse detection  
- School & campus safety model  
- Smart traffic crime detection  

---

## 🤝 Let’s Make India Safer Together 🇮🇳


