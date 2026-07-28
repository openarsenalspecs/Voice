# Cirra Chat

**Cirra Chat** is a modular, all-in-one encrypted communication platform designed to unify messaging across multiple services into a single extensible system.

It provides a centralized architecture for handling conversations, presence, messaging workflows, and platform integrations through a unified interface layer.

Cirra Chat is built to be **fully extensible**, allowing new communication modules, providers, and services to be added as plug-in style components.

---

## 🌐 Overview

Cirra Chat is a **modular communication hub** that enables integration of multiple messaging ecosystems into one unified system.

Unlike traditional chat applications, Cirra Chat is designed as a **framework-level messaging platform**, where each service (WhatsApp, Telegram, SMS, etc.) can function as a connected module within a shared architecture.

It supports:
- Multi-provider messaging architecture
- Unified inbox system
- Real-time communication layer design
- Secure messaging pipeline structure
- Extensible plugin-based service model

---

## ✨ Core Concept

**One system. Many communication providers. Unified experience.**

Cirra Chat enables:
- Centralized message routing across platforms
- Modular integration of external messaging services
- Unified user identity layer (conceptual)
- Cross-platform conversation aggregation
- Consistent messaging UI and data structure

---

## 🧩 Full Feature List

### 🔌 Modular Messaging Architecture
- Plugin-style communication providers
- Independent service adapters per platform
- Unified message schema across all providers
- Extensible provider registry system
- Decoupled messaging logic layer

---

### 💬 Unified Communication System
- Single inbox across all connected services
- One-to-one messaging support
- Group messaging structure support
- Cross-platform conversation threading
- Persistent chat session handling

---

### 🌐 Multi-Provider Integration Layer
Designed to support multiple communication systems through adapters:

- WhatsApp (adapter-ready)
- Telegram (adapter-ready)
- Signal (adapter-ready)
- Messenger (adapter-ready)
- Instagram DMs (adapter-ready)
- SMS / RCS (adapter-ready)
- Discord (integration-ready)
- Slack (integration-ready)
- X / Twitter DMs (integration-ready)

Each provider module supports:
- Standardized message mapping
- Connection state tracking
- Event normalization layer

---

### 💬 Messaging Engine Features
- Message routing system
- Standardized message objects
- Typing event pipeline
- Delivery status tracking:
  - Sent
  - Delivered
  - Read
- Timestamp normalization
- Conversation indexing system

---

### 👤 Identity & Presence System
- Global user presence layer
- Status states:
  - Online
  - Away
  - Do Not Disturb
  - Invisible
- Custom status messages
- Presence synchronization across modules

---

### 🔐 Security Architecture (Design-Level)
- Encryption-first system design
- Secure message transport layer concept
- Provider-level encryption abstraction
- End-to-end encryption readiness
- Identity protection layer (planned)

---

### 📁 Media & Payload System
- Extensible message payload format
- File attachment support structure
- Media type abstraction layer:
  - Images
  - Files
  - Audio
  - Future video support
- Provider-agnostic media handling

---

### 🧠 Core System Behaviors
- Event-driven messaging pipeline
- Reactive state synchronization
- Modular provider event listeners
- Unified chat state management
- Scalable conversation indexing

---

### 🎨 UI Layer (Reference Implementation)
- Glassmorphism-based interface design
- Modular UI components:
  - Sidebar module
  - Chat window module
  - Provider panel module
- Responsive layout system
- Animated state transitions

---

### ⚙️ Developer Architecture
- React-based modular structure
- Component isolation per system module
- Provider abstraction layer
- Central messaging controller
- Extensible plugin architecture design

---

### 🚀 Deployment Capabilities
- Fully browser-based deployment ready
- Compatible with:
  - Vite
  - Create React App
- Deployable on:
  - Vercel
  - Netlify
  - Cloudflare Pages
- Architecture designed for future backend separation:
  - Node.js messaging gateway
  - Microservice provider connectors
  - WebSocket event bus system

---

## ⚙️ Tech Stack

**Frontend Layer:**
- React (functional component architecture)
- React Hooks (state, lifecycle, refs)
- Context API (global system state)
- TypeScript-ready structure

**System Architecture:**
- Modular provider adapter system
- Event-driven messaging pipeline
- Normalized message schema layer
- Plugin-based service architecture

**UI Layer:**
- CSS-in-JS styling system
- Glassmorphism design system
- CSS animations & transitions
- Responsive Flex/Grid layouts
- Lucide React icon system

**State & Data Layer:**
- Centralized messaging state model
- Provider abstraction layer
- In-memory message store (current stage)
- Event-based updates system

**Planned Infrastructure:**
- WebSocket real-time engine
- Node.js messaging gateway
- OAuth provider authentication
- End-to-end encryption service layer
- Distributed message routing system

---

## 🔮 Future Expansion

- Full plugin marketplace for providers
- OAuth-based authentication for messaging services
- Real-time WebSocket messaging engine
- End-to-end encryption implementation (Signal-like architecture)
- AI message routing and prioritization system
- Cross-provider identity unification layer
- Offline message queue synchronization
- Distributed backend microservices

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
  - [https://roxanneardary.com/cirra-chat/](https://roxanneardary.com/cirra-chat/)  

---

## 📜 License & Notice Requirements

Cirra Chat is released under the **GNU Affero General Public License v3.0 or later (AGPL-3.0+)**.  
By contributing to this project, you agree that your contributions will also be released under this license.

Please note the following:

- All contributions must comply with the **AGPL-3.0+** terms.  
- Under **Section 7** of the license, all redistributions, forks, and derivative works must preserve attribution to:  
  **Roxanne Ardary** and **[roxanneardary.com](https://www.roxanneardary.com/)**.  
- Cirra Chat specifications are free to use with attribution. A Specification Branding License can be negotiated upon request.
- The project's **notice.md** file tracks attribution requirements and contributor acknowledgments.  
  Any update that adds new contributors or modifies attribution should also update `notice.md`.  
- When submitting a pull request, ensure that any new files maintain the attribution headers where applicable.
- Network-deployed versions of this software must also remain fully AGPL-3.0+ compliant, including exposure of source code modifications when applicable under the license.  

For full legal details, please refer to the AGPL-3.0+ license and the project's `notice.md` file.

---

## 🔗 Vision

Cirra Chat is a modular communication infrastructure — designed not as a single app, but as a foundation layer for unified messaging systems across platforms.

**Cirra Chat — One System. All Providers. Fully Modular.**  
