# ScribeVault  
**Encrypted, HIPAA-Compliant, AI-Driven.**

ScribeVault is an open-source, AI-driven clinical documentation platform that functions as both a real-time medical scribe and a post-visit summarization engine. Designed for hospitals, clinics, and private practices, ScribeVault provides encrypted, self-hosted patient records; advanced voice interaction; full specialty templates; ICD-10/CPT/SNOMED coding assistance; and C-CDA export for seamless EHR integration.

ScribeVault is licensed under **AGPL 3.0+** with attribution required to **Roxanne Ardary** and **[https://www.roxanneardary.com/](https://roxanneardary.com)** under Section 7.

---

# 🚀 Key Features

## 🔊 Real-Time Voice Scribing
- Live speech-to-text transcription using open-source STT engines (Whisper, WhisperX, etc.)
- Automatically structures documentation into HPI, ROS, Exam, Assessment, Plan, and more
- Noise-optimized for clinic/hospital environments

## 📝 Post-Visit Summarization
- Upload audio for structured note generation  
- Produces clinically coherent SOAP notes  
- Generates ICD-10, CPT, HCPCS, and SNOMED suggestions  
- Supports physician approval and billing workflows  

## 🔐 Encrypted, HIPAA-Compliant Storage
- Fully encrypted PHI pipeline  
- User-selectable storage backend:
  - Encrypted SQLite
  - Encrypted Postgres
  - File-based encrypted vault
  - External FHIR-compatible servers
- Self-hosted **only** — no third-party data exposure

## 🏥 Templates for Every Specialty
ScribeVault includes extensive specialty templates for:
- Internal Medicine, Pediatrics, ER, Psychiatry  
- Surgery, Orthopedics, OB/GYN, Neurology  
- Dermatology, Cardiology, GI, Pulmonology  
- And dozens more  

Templates automatically adapt based on visit type, specialty, symptoms, and provider preferences.

## 🧠 Hybrid AI Stack
- Local LLM inference + optional cloud APIs  
- Supports all major LLM providers:
  - Open-source (Llama, Mistral, Meditron)
  - OpenAI, Anthropic, Google, AWS Bedrock  
  - Custom API endpoints  
- Modular AI pipeline with hot-swappable engines

## 📄 Insurance & EHR Interoperability
- ICD-10, CPT, HCPCS, SNOMED suggestions  
- Insurance-ready documentation  
- CCD / C-CDA export  
- Optional FHIR R4 support  

## 🛡️ Compliance & Security
- HIPAA  
- SOC2 principles  
- GDPR  
- Zero-trust encryption options  
- Extensive audit logging and access controls  

---

# 🔧 Additional Advanced Features

## 🔊 1. Enhanced Voice UX
### Smart Voice Commands  
Control documentation hands-free:
- “Summarize the last two minutes.”
- “Create an assessment.”
- “Insert normal cardiology exam.”
- “Export to C-CDA.”
- “Flag this for billing.”

### Voice Navigation  
Navigate the document with:
- “Go to HPI.”  
- “Open medication list.”  
- “Scroll down.”  

### Wake Word Support  
Optional always-listening mode using a **local-only** wake-word engine (HIPAA-safe).

---

## 👥 2. Patient-Facing Features
### Patient Summary Generator  
Produces non-technical summaries including diagnosis, treatment plan, warning signs, and follow-up instructions.

### Consent Recording & Documentation  
Audio → transcript → encrypted consent record linked to encounter.

### Auto-Curated Patient Education  
Provides clinically validated educational handouts based on diagnosis and demographics.

---

## 🎨 3. UI/UX Enhancements
### Encounter Timeline Visualization  
Chronological transcript timeline showing:
- Speech segments  
- Pauses  
- Decisions and flagged moments

### Confidence Highlighting  
Shades text based on AI certainty to guide clinician review.

### Dual-Pane Workspace  
View real-time transcript and structured note side-by-side for rapid verification.

---

# 🗂️ Architecture Overview
```
┌───────────────────────────┐ ┌──────────────────────────┐
│ Voice Input / Audio File │ │ Manual Text Input │
└─────────────┬─────────────┘ └────────────┬─────────────┘
│ │
▼ ▼
┌──────────────────────────────┐ ┌────────────────────┐
│ STT Engine (Whisper, etc.) │ │ Clinical NLU Layer │
└─────────────┬────────────────┘ └────────────┬──────┘
│ │
▼ ▼
┌──────────────────────────────┐ ┌────────────────────┐
│ AI Reasoning & Note Builder │─────▶│ Coding Engine │
│ (LLMs, Summaries, Templates)│◀────│ ICD-10/CPT/SNOMED │
└─────────────┬────────────────┘ └────────────────────┘
│
▼
┌──────────────────────────────┐
│ Encrypted Storage Backends │
└─────────────┬────────────────┘
│
▼
┌──────────────────────────────┐
│ Exporter (C-CDA, PDF, JSON) │
└──────────────────────────────┘
```


---

# 📦 Installation

## Requirements
- Linux, macOS, or Windows  
- Python 3.10+  
- GPU recommended for real-time STT  
- Docker (optional)

## Docker Install (Recommended)
```bash
git clone https://gitlab.com/Roxanne_Ardary/ScribeVault.git
cd ScribeVault
docker compose up -d
```

# Manual Install
```bash
git clone https://gitlab.com/Roxanne_Ardary/ScribeVault.git
cd ScribeVault
pip install -r requirements.txt
```

# 🔧 Configuration
Environment Variables

Create a .env file:
```
STORAGE_BACKEND=sqlite|postgres|files|fhir
ENCRYPTION_KEY=<your-key>
LLM_PROVIDER=local|openai|anthropic|google|custom
STT_ENGINE=whisper|whisperx|custom
HIPAA_MODE=true
```

# 🖥️ Usage
Start Server
```bash
python serve.py
```

## Real-Time Scribing
1. Start the scribe  
2. Speak normally  
3. Review the structured note  
4. Approve codes  
5. Export  

## Post-Visit Summary
1. Upload audio  
2. Select specialty template  
3. AI generates HPI → Plan → Codes  
4. Approve and export as C-CDA, PDF, or JSON  

---

# 📤 Export Formats
- C-CDA  
- PDF  
- TXT  
- JSON  
- XML  
- Optional FHIR R4  

---

# 🤝 Contributing

ScribeVault welcomes community contributions.  
See **CONTRIBUTING.md** for:

- Issue reporting  
- Code standards  
- Branch naming  
- Security disclosures  
- Testing requirements  
- PR workflow  

---

## Specification Branding License (SBL)

- Fully AGPL-3.0+ compliant system
- Copyleft enforced for network deployments
- Required attribution:
  - Roxanne Ardary
  - https://www.roxanneardary.com/

### Optional

- **Specification Branding License (SBL)**
  - Attribution-free commercial deployment
  - Pricing based on scale, usage, and deployment scope
  - [https://roxanneardary.com/scribevault/](https://roxanneardary.com/scribevault/)

---

## License & Notice Requirements

ScribeVault is released under the **GNU Affero General Public License v3.0 or later (AGPL-3.0+)**.   
By contributing to this project, you agree that your contributions will also be released under this license.

Please note the following:

- All contributions must comply with the **AGPL-3.0+** terms.  
- Under **Section 7** of the license, all redistributions, forks, and derivative works must preserve attribution to:  
  **Roxanne Ardary** and **[roxanneardary.com](https://www.roxanneardary.com/)**.  
- ScribeVault specificiations are free to use with attribution. A Specification Branding License can be negotiated upon request.
- The project's **notice.md** file tracks attribution requirements and contributor acknowledgments.   
  Any update that adds new contributors or modifies attribution should also update `notice.md`. 
- When submitting a pull request, ensure that any new files maintain the attribution headers where applicable.
- Network-deployed versions of this software must also remain fully AGPL-3.0+ compliant, including exposure of source code modifications when applicable under the license.

For full legal details, please refer to the AGPL-3.0+ license and the project's `notice.md` file.

---

# 🛡️ Disclaimer
ScribeVault does not replace professional medical judgment.  
All notes, summaries, and codes must be reviewed and approved by licensed clinicians before use, billing, or insurance submission.
