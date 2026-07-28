# Axis Intelligence

**The Quiet Center of a Smarter Home.**

Axis Intelligence is a modular, open-source ambient AI platform designed to run locally-first, extend endlessly, and give users full ownership of their intelligent environment.

Built under the **GNU Affero General Public License v3.0 or later (AGPL-3.0+)**, Axis Intelligence is designed for transparency, self-hosting, and long-term extensibility across hardware generations.

---

## 🔧 Core Vision

Axis Intelligence is not a smart assistant.

It is a **distributed intelligence system for the home**, built around:

- Privacy-first local execution
- Modular architecture
- Voice-native interaction
- Real-time reasoning and search
- Environmental awareness
- Full user ownership

---

## 🧠 Full Feature List

### 🎙 Voice & Interaction System
- Natural conversational AI interface
- Always-available wake word detection
- Custom voice cloning from a 30-second audio sample
- Multi-user voice recognition
- Emotion-aware response modulation
- Continuous contextual conversation memory

---

### 🧠 AI Intelligence Core
- Local LLM execution via:
  - llama.cpp
  - Ollama runtime
- Support for modern open models:
  - Llama family
  - Mistral / Mixtral-class models
- Tool-using agent architecture (function calling + workflows)
- Multi-agent reasoning system (planner, executor, verifier)

---

### 🔍 Search & Knowledge Layer
- Real-time web search via self-hosted SearXNG
- Retrieval-Augmented Generation (RAG)
- Local semantic memory database
- Persistent household knowledge graph
- Time-weighted recall system (recent + relevant memory balancing)

---

### 🧠 Memory System
- Long-term personal memory storage
- Context-aware recall of preferences and routines
- Household-level shared memory graph
- Per-user memory segmentation
- Privacy-isolated memory layers

---

### 🎧 Audio Intelligence
- Multi-microphone beamforming support
- Direction-of-arrival (DOA) detection
- Spatial audio response rendering
- Room-aware volume adaptation
- Speaker tracking across environments

---

### 🏠 Smart Home Integration
- Deep integration with Home Assistant ecosystems
- Natural language home automation control
- Scene creation via conversational input
- Predictive automation suggestions
- Energy-aware device orchestration

---

### 🎶 Media Brain Module
- Whole-home audio control system
- Voice-driven music playback
- AI-generated playlists based on mood and context
- Podcast and audiobook continuation system
- Local media server integration
- Cross-room synchronized playback

---

### 🧑‍🏫 Education Mode Module
- Interactive tutoring system
- Homework assistance with step-by-step reasoning
- Language learning conversations
- Quiz and knowledge reinforcement system
- Safe family learning profiles

---

### 👁 Vision Module (Optional Expansion)
- Object detection and recognition
- Gesture-based interaction
- Environmental awareness (lights, doors, presence)
- Visual memory indexing (user-controlled)

---

### 🔐 Privacy & Security Module
- Fully local-first execution by default
- Optional encrypted audit logging
- No telemetry or forced cloud dependency
- Transparent execution tracing
- User-controlled data retention policies

---

### ⚙ Modular Architecture System
Every subsystem is independently replaceable:

- Voice Engine Module  
- Wake Word Module  
- LLM Reasoning Module  
- Memory Module  
- Search Module  
- Audio Spatial Module  
- Media Module  
- Education Module  
- Smart Home Module  
- Vision Module  
- Security Module  
- Plugin/Extension Module  

Modules can be:
- Swapped
- Disabled
- Upgraded
- Forked independently
- Rewritten in any language

---

## 🧩 Technology Stack

### 🧠 AI & ML
- llama.cpp (local inference runtime)
- Ollama (model orchestration)
- Whisper / faster-whisper (speech recognition)
- XTTS (voice cloning & TTS)
- openWakeWord (wake detection)
- Qdrant / Chroma (vector memory)

### 🔍 Search & Agents
- SearXNG (self-hosted search)
- LangGraph-style agent workflows
- RAG-based retrieval systems

### 🎧 Audio Processing
- Pyroomacoustics (spatial audio + DOA)
- Beamforming microphone arrays
- PipeWire / ALSA audio stack

### 💻 Hardware Layer
- NVIDIA Jetson Orin family (edge AI acceleration)
- Raspberry Pi (lightweight deployments)
- Seeed Studio mic array hardware
- Standard Linux-based systems

---

## 🏗 Design Philosophy

Axis Intelligence is built around five core principles:

1. **Local-first computation**
2. **Modular system design**
3. **User ownership of intelligence**
4. **Transparency over abstraction**
5. **Long-term hardware evolution**

---

## 🔌 Extensibility

Axis supports:

- Plugin system for community modules
- Custom AI skill creation
- Third-party integrations
- Self-hosted deployments
- Enterprise or household scaling

---

## 📦 Installation (High-Level)

Axis is designed to be deployed as modular services:

1. Install base Linux environment  
2. Deploy core runtime (LLM + audio stack)  
3. Enable modules as needed  
4. Configure local or mesh deployment  
5. Connect optional hardware (mic arrays, sensors)

---

## Specification Branding License (SBL)
### Standard
- Fully AGPL-3.0+ compliant system
- Copyleft enforced for network deployments
- Required attribution:
  - Roxanne Ardary
  - https://www.roxanneardary.com/

### Optional

- **Specification Branding License (SBL)**
  - Attribution-free commercial deployment
  - Pricing based on scale, usage, and deployment scope
  - [https://roxanneardary.com/axis-intelligence/](https://roxanneardary.com/axis-intelligence/)

---

## 📜 License & Notice Requirements

Axis Intelligence is released under the **GNU Affero General Public License v3.0 or later (AGPL-3.0+)**.   
By contributing to this project, you agree that your contributions will also be released under this license.

Please note the following:

- All contributions must comply with the **AGPL-3.0+** terms.  
- Under **Section 7** of the license, all redistributions, forks, and derivative works must preserve attribution to:  
  **Roxanne Ardary** and **[roxanneardary.com](https://www.roxanneardary.com/)**.  
- Axis Intelligence specificiations are free to use with attribution. A Specification Branding License can be negotiated upon request.
- The project's **notice.md** file tracks attribution requirements and contributor acknowledgments.  
  Any update that adds new contributors or modifies attribution should also update `notice.md`.
- When submitting a pull request, ensure that any new files maintain the attribution headers where applicable.
- Network-deployed versions of this software must also remain fully AGPL-3.0+ compliant, including exposure of source code modifications when applicable under the license.

For full legal details, please refer to the AGPL-3.0+ license and the project's `notice.md` file.

---

## 🚀 Status

Axis Intelligence is in early development and architecture design phase.

The goal is to evolve into a fully open, community-driven ambient intelligence platform for real-world deployment.

---

**Axis Intelligence**  
*The Quiet Center of a Smarter Home.*
