# SpeakOps

<div align="center">
  <img src="https://github.com/speakops/assets/blob/main/branding/speakops_pulsar_logo.png" alt="The Signal" width="128">
  <br>
  <b>DevOps for your Voice</b>
</div>

---

## 📡 The Concept

**Real-time speech telemetry.**

SpeakOps is a hybrid AI system that analyzes your speech in real-time (Interviews, Sales Calls, Keynotes) and provides a HUD-style teleprompter on your phone with behavioral nudges.

> "It's like having a spin doctor in your pocket."

---

## 🛰️ Architecture

| Component | Tech Stack | Role |
| :--- | :--- | :--- |
| **desktop** | **Next.js / FastAPI**. The central dashboard and interview simulator. | *Mission Control* |
| **cloud** | **Python / Whisper / Llama 3**. Heavy lifting inference and analysis API. | *The Brain* |
| **phone** | **PWA**. Low-latency websocket client for real-time cues. | *The Receiver* |

---

## 📶 Features

- **Pacing**: "Slow down, you're at 180wpm."
- **Filler Word Detection**: Real-time counters for "um," "like," "actually."
- **Sentiment Analysis**: "You're sounding defensive. Pivot to curiosity."
- **Privacy First**: Local STT options for sensitive conversations.

---

## 🔗 Connect

- **Maintainer**: [@skew202](https://github.com/skew202) (Stefan Wiest)
