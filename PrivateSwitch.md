# PrivateSwitch

**From one line to total control.**  
*Private, AI-powered call routing you fully own.*

PrivateSwitch is a self-hosted, open-source phone routing system that transforms a single number into a fully controlled, intelligent switchboard. Built with privacy at its core, PrivateSwitch integrates AI (Phonic) to screen, route, and manage calls—giving you complete ownership over your communication.

---

## 🚀 Overview

PrivateSwitch acts like a modern-day operator:

- Intercepts inbound and outbound calls  
- Uses AI to understand caller intent  
- Routes calls based on rules, context, and preferences  
- Encrypts all communication  
- Supports multiple numbers for personal, family, or small office use  

---

## ✨ Features

### 📞 Core Call Management
- Inbound and outbound call routing  
- Multi-number support (DID management, 1–10+ numbers)  
- Custom routing rules per number  
- Call forwarding (conditional and unconditional)  
- Simultaneous and sequential call ringing  
- Voicemail with transcription  
- Call recording (configurable and encrypted)  
- Call transfer (blind, attended, AI-assisted)  

---

### 🧠 AI Operator (Phonic Integration https://gitlab.com/Roxanne_Ardary/phonic)
- AI call answering and greeting  
- Natural language caller interaction  
- Caller intent detection and classification  
- Smart call screening (“Who is calling and why?”)  
- AI-based routing decisions  
- Context-aware responses (memory of past calls)  
- Personalized AI voices per number  
- Real-time conversation intervention (takeover or assist)  

---

### 🔁 Intelligent Routing Engine
- Rule-based routing (time, caller ID, keywords)  
- AI-driven dynamic routing  
- Priority routing (VIP / whitelist callers)  
- Blacklist and spam auto-blocking  
- Multi-destination routing trees  
- Failover routing (fallback numbers or voicemail)  
- Geo-based routing (optional)  

---

### 🔐 Privacy & Encryption
- End-to-end encrypted signaling (SIP over TLS)  
- Encrypted media streams (SRTP)  
- Encrypted call recordings and logs  
- Self-hosted infrastructure (full data ownership)  
- Zero-knowledge storage options  
- Per-number privacy configurations  
- Secure key management  

---

### 🛡️ Spam & Call Protection
- AI-powered robocall detection  
- Behavioral spam analysis  
- Challenge-response system (AI verification)  
- Silent screening and filtering  
- Reputation scoring for unknown callers  
- Automatic spam blocking and reporting  

---

### 👤 Identity & Caller Intelligence
- Caller recognition and tagging  
- Voice fingerprinting (optional)  
- Contact-based routing rules  
- Call history with contextual notes  
- Relationship-aware handling (family, business, unknown)  

---

### 📊 Dashboard & Control Panel
- Web-based management interface  
- Real-time call monitoring  
- Call logs with search and filtering  
- Voicemail and recording playback  
- Number configuration and assignment  
- Routing rule builder (visual + advanced)  
- AI behavior customization  
- User and role management (for families or teams)  

---

### 🏠 Multi-User / Multi-Line Support
- Up to 10+ independent phone numbers  
- Separate profiles per number (family, office, personal)  
- Shared or isolated routing logic  
- Role-based access (admin, user, viewer)  
- Group call handling (household or small office)  

---

### 📤 Outbound Calling & Automation
- AI-assisted outbound calls  
- Scheduled calls and reminders  
- Call scripting with dynamic responses  
- Callback automation  
- Contact list integration  

---

### 🔌 Integrations & Extensibility
- SIP provider compatibility (bring your own carrier)  
- API for custom integrations  
- Webhooks for call events  
- CRM integration (optional)  
- Plugin architecture for extensions  
- Support for third-party AI modules  

---

### 🌐 Self-Hosting & Deployment
- Fully self-hosted (on-premise or cloud VPS)  
- Docker-based deployment  
- Lightweight and scalable architecture  
- LAN-only or internet-accessible modes  
- Backup and restore functionality  

---

### 📡 Advanced Telephony Features
- IVR (interactive voice response) builder  
- Call queues and hold management  
- Ring groups  
- Time-based availability (business hours, do-not-disturb)  
- Custom greetings and prompts  
- Multi-language support  

---

### 🧩 Future / Expandable Features
- Federated PrivateSwitch network (secure node-to-node calling)  
- End-to-end encrypted peer calling between users  
- Decentralized identity integration  
- Advanced analytics and insights  
- Mobile app for control and notifications  
- Hardware appliance version (plug-and-play router device)  

---

## 🏗️ Architecture (High-Level)

PrivateSwitch combines:

- A telephony engine (PBX) for call handling  
- An AI layer (Phonic) for interaction and decision-making  
- A routing engine for logic and control  
- A secure encryption layer for privacy  
- A web dashboard for configuration and monitoring  

---

## 🛠️ Use Cases

- Personal call screening and spam blocking  
- Family call management with shared control  
- Small office virtual receptionist  
- Privacy-focused communication systems  
- AI-assisted outbound calling and automation  

---

## 🤝 Contributing

Contributions are welcome and encouraged. Please review contribution guidelines and ensure compliance with licensing and attribution requirements.

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
  - [https://roxanneardary.com/privateswitch/](https://roxanneardary.com/privateswitch/)

---

## License & Notice Requirements

PrivateSwitch is released under the **GNU Affero General Public License v3.0 or later (AGPL-3.0+)**.   
By contributing to this project, you agree that your contributions will also be released under this license.

Please note the following:

- All contributions must comply with the **AGPL-3.0+** terms.  
- Under **Section 7** of the license, all redistributions, forks, and derivative works must preserve attribution to:  
  **Roxanne Ardary** and **[roxanneardary.com](https://www.roxanneardary.com/)**.
- The project's **notice.md** file tracks attribution requirements and contributor acknowledgments.   
  Any update that adds new contributors or modifies attribution should also update `notice.md`. 
- When submitting a pull request, ensure that any new files maintain the attribution headers where applicable.
- Network-deployed versions of this software must also remain fully AGPL-3.0+ compliant, including exposure of source code modifications when applicable under the license.

For full legal details, please refer to the AGPL-3.0+ license and the project's `notice.md` file.
