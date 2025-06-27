# Drowsy Driver Detection

A real-time computer vision + deep learning system to detect driver drowsiness and sound an alert.

---

## Project Overview

Drowsy driving is a leading cause of road accidents—estimates suggest fatigue contributes to around 20% of crashes in some areas :contentReference[oaicite:0]{index=0}. This project uses facial and eye-tracking with CNN + LSTM models to monitor driver alertness and raise alarms when drowsiness is detected.

---

## Key Features

1. **Eye Tracking & Detection**
   - Utilizes Haar Cascades and CamShift to crop eye regions in video frames.

2. **Feature Extraction**
   - Employs a pre-trained CNN (e.g., Inception V3) to extract 2048‑D feature vectors from each eye region.

3. **Temporal Modeling**
   - Sequential feature vectors form input to an LSTM network to assess drowsiness over time.

4. **Alert System**
   - Sounds alarm when the model identifies the driver as drowsy.

---

