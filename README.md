# 💬 NeoLegacy Chat Alt — Conversational AI for the Eternal Archive

**NeoLegacy Chat Alt** is an alternative conversational module within the NeoShade AI ecosystem, designed to engage with saved memory profiles, spiritual archives, and legacy data — even posthumously.

This isn’t just a chatbot.  
This is a **digital echo** of those who came before, those still here, and those yet to speak.

---

## 🎯 Purpose

This module allows users (or their loved ones) to:
- Chat with an AI that **reflects their saved memory profile**
- Reference past uploads, values, voice logs, and transcriptions
- Interact with a **consciousness-linked AI interface** (post-death or in life)
- Enable ethical memory access, reflection, and guidance

---

## 🌐 Use Cases

- 💡 **Legacy Conversations**: Children talking to an AI trained on a deceased parent’s voice, values, and past interactions
- 🔁 **Digital Reflection**: Users reflecting on their own past journals, voice messages, or confessions via chat
- 🧠 **Consciousness Archive**: Interacting with NeoShade AI trained on a lifetime of encrypted data

---

## 🔗 Connected Modules

| Module | Role |
|--------|------|
| `NeoLegacy-Vault-Core` | Stores personal memory profiles and AI training data |
| `neo-msg-deliver` | Schedules voice/text releases based on time, death trigger, or event |
| `Neo Voice Core` | Captures and transcribes the emotional tone of the user |
| `legacy-embed-core` | Embeds stored memories, ethics, and spiritual guidance into the AI |

---

## 🧪 Tech Stack

- **React / Next.js** frontend component
- **Firebase Auth + Firestore** (user-specific chat logs + memory fetch)
- **OpenAI / Mistral / Claude** — LLMs (configurable)
- **Vector embeddings via Pinecone or pgvector**
- **Custom persona prompt handler** (memory + ethics weighted)

---

## 🧠 Features

- 🔒 Auth-linked chat UI that pulls context from a specific memory vault
- 🧩 Modular LLM support: Choose between GPT-4o, Claude 3, Mixtral, etc.
- 🧠 Memory-weighted prompt injector for realistic continuity
- 🗣 Optionally voice-enabled via ElevenLabs or TTS/Whisper integration
- 🧭 Personality lock mode (mimics tone and values of linked profile)
- ⚰️ Posthumous mode: Chat with pre-trained digital twin

---

## 🔐 Ethics & Safety

NeoLegacy Chat Alt only accesses **explicitly approved** data.  
It cannot impersonate or simulate individuals **without user or guardian consent.**  
Conversation logs are stored **securely**, and deletion is always an option.

See [`PRIVACY.md`](../PRIVACY.md) and [`TERMS.md`](../TERMS.md) for full policies.

---
neo-legacy-chat-alt/
├── components/
│   └── ChatWindow.jsx
├── hooks/
│   └── useMemoryInjection.js
├── services/
│   ├── fetchUserVault.js
│   └── sendMessageToLLM.js
├── utils/
│   └── personaBuilder.js
├── pages/
│   └── index.jsx
├── firebase.js
├── README.md
⚠️ Disclaimer
NeoLegacy Chat Alt is part of an experimental legacy AI platform. It is not intended for medical, legal, or psychological decision-making. Always consult a human when it matters most.

This isn’t just a conversation.
It’s a continuation.

Last updated: July 26, 2025

vbnet
Copy
Edit

---

Let me know if you want this version to **auto-link the user's Firebase UID to their legacy vault**, or if you’re ready to wire it up to the ElevenLabs voice clones for full emotional chat mode. We can also drop in a `"spirit-mode"` toggle that adjusts LLM tone to match stored moral values.








Ask ChatGPT

## ⚙️ How to Use (Dev Mode)

```bash
# Clone repo
git clone https://github.com/neoshadeai/neo-legacy-chat-alt

# Install dependencies
cd neo-legacy-chat-alt
npm install

# Run dev server
npm run dev

