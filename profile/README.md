<div align="center">

# medix-ai

**AI-powered solutions that make expert medical care accessible to everyone**

We build clinical-grade AI tools that close the gap between hospital visits — turning smartphones into monitoring devices and making personalized care possible at home.

---

## Focus Areas

- **Remote Patient Monitoring** — continuous AI assessment between clinic visits
- **Computer Vision for Healthcare** — wound analysis, joint tracking, skin evaluation
- **Personalized Rehabilitation** — adaptive care plans based on individual recovery data
- **Multimodal AI** — combining image, sensor, and clinical data for better outcomes

---
---

## Featured Project

### 🫀 [SonoCube](https://medix-ai.github.io/sonocube/) — AI Cardiac EF Analysis

Research-grade macOS software that **automatically estimates ejection fraction (EF)** from echocardiogram videos.
Drag in an AVI · DICOM file and SonoCube handles the rest — ED/ES frame detection → AI EF inference → PDF report.

- **On-device inference** — runs locally on CPU with a lightweight ONNX model (~60KB); no video data leaves the device
- **Automatic frame detection** — LVSegEngine (U-Net, Dice 0.930) detects ED/ES frames without manual selection
- **Performance** — MAE 8.01%, r=0.614 on the EchoNet-Dynamic test set
- **Reporting** — auto-generated PDF with EF range visualization, frame statistics, and quality warnings

[![Live](https://img.shields.io/badge/Live-medix--ai.github.io-4285F4?style=flat&logo=googlechrome&logoColor=white)](https://medix-ai.github.io/sonocube/)
[![Repo](https://img.shields.io/badge/Code-sonocube__poc-181717?style=flat&logo=github&logoColor=white)](https://github.com/medix-ai/sonocube_poc)
[![Platform](https://img.shields.io/badge/Platform-macOS-000000?style=flat&logo=apple&logoColor=white)](https://github.com/medix-ai/sonocube_poc/releases)

> ⚠️ Research use only. Not a medical device. Not for clinical diagnosis.

---
---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-FA7343?style=flat&logo=swift&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Gemma](https://img.shields.io/badge/Gemma-4285F4?style=flat&logo=google&logoColor=white)

---

<div align="center">

*Bridging the gap between hospital visits with AI.*

</div>
