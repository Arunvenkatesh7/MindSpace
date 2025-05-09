# 🧠 VR Mental Health Therapy Platform

[![Project Demo](https://img.shields.io/badge/Demo-Watch%20Video-red)](https://your-demo-video-link)
[![Google Drive](https://img.shields.io/badge/Google%20Drive-Download%20Project-blue)](https://drive.google.com/file/d/1L3NFVBg6SqqoRrZfCVlknxoJZRbOJOCY/view?usp=drive_link)


A comprehensive Virtual Reality (VR) application designed to address various mental health challenges through immersive, interactive experiences. This platform leverages psychological principles such as exposure therapy, cognitive behavioral techniques, guided relaxation, and biofeedback mechanisms across multiple therapeutic modules.

## 🔍 Project Overview

This VR mental health platform consists of several interconnected therapeutic modules:

1. **🧙‍♂️ VR Psychiatrist** - AI-powered virtual counseling sessions
2. **😨 Fear Simulator** - Exposure therapy for common phobias
   - Acrophobia (fear of heights)
   - Aquaphobia (fear of water)
   - Glossophobia (fear of public speaking)
3. **😤 RageRoom Game** - Emotional catharsis and stress relief
4. **🐦 Breathing Bird Game** - Breathing regulation and mindfulness training

## 📋 Module Details

### 🧙‍♂️ VR Psychiatrist

An AI-driven counseling system that processes verbal responses about sleep patterns, appetite, lifestyle habits, and emotional well-being to provide therapeutic feedback.

**Technical Implementation:**
- Audio input processing using ASR models (OpenAI's Whisper)
- Sentiment and behavioral analysis through NLP techniques
- LLM-based response generation (LLaMA/GPT models)
- Therapeutic feedback system for actionable recommendations

**Performance Metrics:**
- 94% content relevance score in Single Turn Evaluation
- High effectiveness in generating therapeutically valuable responses

### 😨 Fear Simulator

Interactive VR environments designed to address specific phobias through progressive exposure therapy.

**Environments:**
- **Virtual Skydiving (Acrophobia)** - Navigate through floating rings during descent
- **Underwater Exploration (Aquaphobia)** - Explore colorful coral structures while answering MCQs
- **Public Speaking Simulation (Glossophobia)** - Deliver speeches to virtual audiences

**Performance Metrics (Glossophobia):**
- 93.2% accuracy in speech transcription (Whisper)
- 89.7% correctness in anxiety level assessment (Google Gemini)
- 76% improvement in confidence scores after multiple sessions

### 😤 RageRoom Game

A virtual environment for emotional catharsis through interaction with destructible objects.

**Technical Implementation:**
- Physics-based collision detection and simulation
- Real-time object reactions (shattering, bouncing, deformation)
- Impact-based stress reduction analysis and tracking

### 🐦 Breathing Bird Game

An interactive game that teaches diaphragmatic breathing techniques through gameplay controlled by breathing patterns.

**Technical Implementation:**
- Real-time respiration detection via breath sensors
- Breath-activated control mechanisms (inhale to rise, exhale to descend)
- Navigation through environmental challenges (gas walls, flame throwers, ice shards)
- Stress reduction tracking and relaxation scoring

#### Key Features

- 🎮 **Breath-Controlled Gameplay**  
  Actions are triggered by breathing patterns—each level presents new tasks where inhaling or exhaling performs specific moves like flying, jumping, or dodging obstacles.
- 🌬️ **Dynamic Instructions**  
  Instructions for which breath triggers which action are updated in real time, helping users stay engaged and responsive.
- 🧠 **Mental Health Benefits**  
  Encourages healthy breathing that activates the parasympathetic nervous system, reduces stress, and improves emotional regulation.
- 🌋 **Obstacle-Rich Environment**  
  Navigate through hazards such as poison gas, flame throwers, and ice shards—each demanding a different type of breath control to overcome.
- 📈 **Progressive Challenge**  
  As players advance, breathing tasks grow more complex, improving adaptability and breathing technique flexibility.

## 🛠️ Technologies Used

- Unity Game Engine for VR development
- Large Language Models (LLaMA, GPT, Google Gemini)
- Automatic Speech Recognition (OpenAI's Whisper)
- Natural Language Processing for sentiment analysis
- Physics simulation engines
- Real-time biofeedback and respiration sensors
- VR headsets and controllers

## 📦 Installation

1. **Access the project**
   
   **Option 1: GitHub Repository**
   ```bash
   git clone https://github.com/your-username/vr-mental-health-platform.git
   cd vr-mental-health-platform
   ```
   
   **Option 2: Google Drive**
   The complete project is also available on Google Drive:
   [Download VR Mental Health Therapy Platform](https://drive.google.com/drive/folders/your-drive-folder-link)

2. **Hardware Requirements**
   - VR headset compatible with Unity
   - Breath sensors (for Breathing Bird game)
   - Microphone (for VR Psychiatrist and Glossophobia modules)

3. **Software Setup**
   - Open the project in Unity (2021.3 or newer recommended)
   - Install required packages from the Unity Package Manager
   ```bash
   # For API connections (if using standalone Python components)
   pip install -r requirements.txt
   ```

4. **Configure API Keys**
   - Set up necessary API keys for LLM services in the `config.json` file

5. **Run the application**
   - Build and run the VR application through Unity
   - Or play directly in the Unity Editor for testing

## 📚 Research Basis

This platform integrates evidence-based therapeutic approaches:
- Exposure therapy principles for phobia treatment
- Cognitive Behavioral Therapy (CBT) techniques
- Mindfulness and breathing regulation for stress management
- Emotional catharsis theories for anger management

## 🧪 Future Enhancements

- Integration of physiological sensors (heart rate, GSR) for more accurate biofeedback
- Adaptive difficulty based on user performance and anxiety levels
- Expanded phobia treatment modules
- Cloud-based progress tracking and therapist dashboard
- Mobile VR support for increased accessibility

## 🤝 Contribution

Researchers, developers, and mental health professionals are welcome to contribute to this project. Please feel free to fork this repository and submit pull requests.

## 📄 License

MIT License – see LICENSE file for details.

## 🙏 Acknowledgements

- Inspired by evidence-based therapeutic techniques in clinical psychology
- Special thanks to the developers, researchers, and mental health professionals contributing to the advancement of VR therapy tools
