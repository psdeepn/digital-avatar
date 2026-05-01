# 🧠 Haleon Digital Avatar Chatbot

A real-time conversational AI system built in Unity that combines **speech recognition, intent detection, structured conversation flows, and avatar interaction** to simulate a digital human experience.

---

## 🎯 Overview

This project transforms traditional UI-based healthcare interaction into a **voice-driven conversational system**.

Instead of clicking buttons, users can **speak naturally**, and the avatar responds with synchronized **voice, animation, and subtitles**.

---

## ⚡ Key Features

### 🎤 Speech Input System
- Push-To-Talk
- Always Listening
- Voice Activation (adaptive threshold)
- Real-time mic level detection

---

### 🧠 Speech Recognition Engine
- Built using Windows `DictationRecognizer`
- Processing lock system (prevents duplicate triggers)
- Recognition state control
- Auto-recovery on failure

---

### 🎯 Intent Detection
- Lightweight keyword-based matching
- Categories:
  - Oral Care
  - Cold & Flu
  - Migraine
- Ambiguity handling & fallback logic

---

### 🔁 Conversation Flow Engine (Core System)
- Structured decision-based system (not random AI)
- Supports:
  - Yes / No branching
  - Continue-based flow
  - Automatic transitions
  - Final exit states
- Ensures predictable and safe responses

---

### 🎭 Avatar System
- Animation synced with audio playback
- Talking / Idle states
- Creates human-like interaction

---

### 💬 Subtitle System
- Word & letter typing modes
- Sentence splitting using Regex
- Audio-synced timing
- Smooth fade transitions

---

### 🎮 Interaction System
- Keyboard, Mouse, Gamepad support
- USB presenter compatibility
- Manual demo mode for presentations

---

### 🎥 Camera & UI System
- Cinemachine camera switching
- Animated UI panels
- Auto-hide & hover interactions

---

### 🖼️ Multimedia Support
- Popup images during conversation
- Video intro system

---

## 🏗️ System Architecture

User Voice
↓
Speech Recognition
↓
Intent Detection
↓
Conversation Flow Engine
↓
Response Generation
↓
Avatar + Audio + Subtitles

---

## 🧩 Core Scripts

| Script | Responsibility |
|------|---------------|
| `WindowsSpeechToText` | Handles mic input & speech recognition |
| `SpeechInputManager` | Controls mic modes & voice activation |
| `IntentMatcher` | Detects user intent |
| `NPCResponseController` | Manages conversation flow |
| `SubtitleUI` | Displays animated subtitles |
| `ManualDemoController` | Handles presentation/demo flow |
| `CinemachineCameraSwitcher` | Controls camera transitions |
| `MicDeviceManager` | Handles microphone switching |

---

## 🚧 Challenges & Solutions

### Challenges
- Speech detection delays
- Noise interference
- Duplicate input triggers
- Sync between audio & animation

### Solutions
- Adaptive voice threshold
- Processing lock system
- State-based flow control
- Auto-recovery for speech engine

---

## 🚀 Future Scope

- Emotion-aware AI responses  
- Multilingual support  
- GPT-based conversational intelligence  
- VR integration (Unity XR)  
- Personalized user experiences  

---

## 🧠 Key Learning

This project demonstrates:
- Real-time system design  
- State management in interactive systems  
- Voice-based UX design  
- Modular architecture in Unity  

---

## 🎬 Demo

> Live demo available during presentation  
> (Unity WebGL build can be embedded here)

---

## 👨‍💻 Author

**Sai Deepak**  
Senior Designer & Developer (XR / VR)  

---

## 📌 Note

This is not a basic chatbot —  
it is a **real-time conversational system designed for immersive user interaction**.
