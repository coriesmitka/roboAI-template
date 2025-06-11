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
```

## 🧰 Technologies

- Python 3.x (modular control and integration scripts)
- Webots (physics-based robot simulation)
- Vosk (offline speech-to-text integration)
- pyttsx3 and gTTS (text-to-speech for verbal interaction)
- Planned: Unity ML-Agents, Isaac Sim, Raspberry Pi + Petoi Bittle

---

## :clipboard: Project Status

| Module      | Description                                 | Status        |
|-------------|---------------------------------------------|----------------|
| Module 1    | Simulator Selection + Environment Setup     | ✅ Completed    |
| Module 2    | Webots Hello World + Basic Movement         | 🔄 In Progress  |
| Module 3    | Python Controller Integration               | ⬜ Planned      |
| Module 4    | Voice Command Recognition (STT)             | ⬜ Planned      |
| Module 5    | Voice Output Integration (TTS)              | ⬜ Planned      |
| Module 6    | Walking Motion + Behavior Tuning            | ⬜ Planned      |
| Module 7    | Upgrade Path: Unity/Isaac/Hardware Export   | ⬜ Planned      |

