# V.A.L.I.D 🛡️🎙️
> **AI-Powered Real-Time Detection and Prevention of Voice Cloning Impersonation Attacks**

[![SIH Problem Statement](https://img.shields.io/badge/SIH2026-SIH26104-blue.svg)](https://sih.gov.in/)
[![Domain](https://img.shields.io/badge/Domain-Blockchain%20%26%20Cybersecurity-orange.svg)]()
[![Python](https://img.shields.io/badge/Python-3.10%2B-brightgreen.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

**VoiceShield AI** is an end-to-end, ultra-low-latency security framework built to detect, alert, and block synthetic voice audio and deepfake impersonation attacks in real time. Designed specifically for VoIP networks, telephony gateways, and mobile applications, VoiceShield AI combines deep acoustic analysis, neural biomarker detection, and blockchain-based audit logging to secure voice communications.

---

## 📌 Problem Overview (SIH26104)

With the rapid proliferation of generative AI models (such as ElevenLabs, VALL-E, and Tortoise-TTS), voice cloning attacks have emerged as a severe threat to financial systems, enterprise helpdesks, emergency services, and personal privacy. Traditional audio detection methods suffer from high processing latency and fail when subjected to real-world telephony compression.

**VoiceShield AI** addresses this challenge by providing:
1. **Real-time inference** under 200 ms latency.
2. **Robustness** against compressed telecommunication codecs (GSM, G.711, Opus).
3. **Tamper-proof forensics** via decentralized event logging.

---

## ✨ Key Features

- **⚡ Real-Time Spectral Analysis:** Extracts MFCCs, bispectrum features, phase inconsistencies, and pitch variability on live streaming audio.
- **🫁 Neural Biomarker & Liveness Verification:** Monitors micro-pauses, artificial breathing patterns, and dynamic challenge-response inputs to prevent synthetic playback attacks.
- **🛡️ Adversarial & Codec Resilience:** Pre-processing pipelines trained on noise-augmented, compressed cellular/VoIP audio streams.
- **📊 Real-Time Dynamic Risk Scoring:** Continuously updates a 0–100% impersonation risk index frame-by-frame during active calls.
- **⛓️ Tamper-Proof Audit Trail:** Anchors threat detections, cryptographic hashes, and forensic metadata directly onto a blockchain ledger.
- **🔍 Explainable AI (XAI) Dashboard:** Visual telemetry featuring audio spectrogram heatmaps, pitch tracking, and synthetic anomaly markers for forensic reporting.

---
## 🛠️ Tech Stack

* **ML / Audio Inference:** PyTorch, ONNX Runtime, librosa, PyWorld, Torchaudio
* **Real-Time Streaming:** WebSockets, WebRTC, PyAudio, FastAPI
* **Frontend / Dashboard:** React.js, TailwindCSS, Chart.js / Recharts
* **Blockchain Log:** Solidity, Ethereum / Polygon (Hardhat / Ethers.js)
* **Deployment & Edge:** Docker, ONNX / TensorRT, Quantized TFLite

---

## 🚀 Getting Started

### Prerequisites

* Python 3.10+
* Node.js v18+
* FFmpeg installed locally

### Installation

1. **Clone the Repository**
   ```bash
   git clone [https://github.com/usebonded/V.A.L.I.D.git](https://github.com/usebonded/V.A.L.I.D.git)
   cd V.A.L.I.D
