# 🤖 Robo AI – Learning to Walk and Talk

## 📝 Project Overview
Robo AI is an interactive robotics simulation project designed to teach a small virtual robot how to walk and respond to human voice commands. This project leverages physics-based simulation, speech recognition, and Python-based control logic to explore human-machine learning in a virtual environment. The initial development uses Webots with future expansion planned to advanced simulators and physical robots.

---

## 🎯 Purpose
- Simulate robotic movement (walking, turning, balance)
- Integrate voice input/output to enable basic interaction
- Prototype logic and control within Webots before scaling
- Explore reinforcement learning and voice-AI integrations
- Lay the groundwork for eventual deployment to real-world robotics

---

## 📁 Project Structure
```plaintext
robo-ai/
├── simulation/         # Webots world and robot config files
├── control/            # Python controllers for robot motion
├── voice/              # STT and TTS integration modules
├── data/               # Training logs, saved speech input, model files
├── docs/               # Architecture, planning notes, diagrams
├── output/             # Exported runs, GIFs, or demo logs
├── requirements.txt    # Python dependencies
└── README.md           # Project summary and setup info

## 🧰 Technologies

**Simulation**  
- Webots (https://cyberbotics.com/)

**Programming Language**  
- Python 3.x

**Speech Recognition**  
- Vosk (offline speech-to-text) – https://alphacephei.com/vosk/

**Text-to-Speech (TTS)**  
- pyttsx3 – https://pypi.org/project/pyttsx3/  
- gTTS (Google Text-to-Speech) – https://pypi.org/project/gTTS/

**Planned Upgrades**  
- Unity ML-Agents (reinforcement learning)  
- NVIDIA Isaac Sim (realistic physics and synthetic data)  
- Raspberry Pi or Petoi Bittle for hardware deployment


## 📌 Project Status

- ✅ Simulator selected: Webots
- 🔄 Installation and Hello World test: In Progress
- ⬜ Python control logic: Not Started
- ⬜ Voice command integration: Planned
- ⬜ Walking motion tuning: Planned
- ⬜ Reinforcement learning phase: Planned
- ⬜ Upgrade to Unity / Isaac / hardware: Planned

