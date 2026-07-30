# 🧠 Silent Struggles
### AI-Powered Early Mental Health Detection & Support Platform
> Built for **Smart India Hackathon 2025** | Ministry of Health & Family Welfare | Theme: Healthcare & Mental Health

---

## 📌 Problem Statement

India has **150M+ people** who need mental health care, yet **83% never receive any treatment**. The most silenced groups — **women, elderly, and disabled individuals** — face compounding barriers: stigma, language, digital exclusion, and a critical shortage of psychiatrists (1 per 100,000 in rural India).

Existing apps like Wysa and iCall are **reactive** — they require users to already recognize their distress. Most never do.

**Silent Struggles** flips that model — detecting distress *before* crisis, in the user's own language, on any network.

---

## ✨ Features

### 💬 Multilingual Mood Check-in
- Daily emotional check-ins via text in **10+ Indian regional languages**
- Real-time **NLP sentiment analysis** — detects positive, negative, and crisis-level language
- Animated **Wellness Pulse orb** that responds to mood state visually

### 🤖 AI Risk Scoring Engine
- Live **Low / Medium / High risk classification** based on mood + journal input
- Crisis language detection with **automatic escalation** to NIMHANS and iCall helplines
- Dynamic risk meter updated in real time with every check-in

### 📊 Passive Digital Biomarkers
- On-device analysis of typing rhythm, app usage patterns, voice tone, and response speed
- **Zero data transmitted** — all ML inference runs locally (TensorFlow Lite architecture)
- Full offline support — works on **2G networks**

### 🤝 Anonymous Peer Support Circles
- Separate communities for **New Mothers**, **Elderly**, and **Disability & Dignity**
- AI moderation scans every post for crisis language before publishing
- Anonymous posting with like, reply, and peer solidarity interactions

### 📚 Gamified Mental Health Literacy
- **6 lessons** covering Anxiety, Depression, PPD, Stigma, Elderly Mental Health, and Crisis Recognition
- Interactive quizzes with medically accurate explanations
- XP system, badges, and progress tracking to encourage consistent learning

### 🆘 Crisis Support Hub
- Real Indian helplines: **iCall (9152987821)**, **Vandrevala (1860-2662-345)**, **NIMHANS (080-46110007)**, **SNEHI**
- **City-based facility finder** — returns real government and NGO mental health centers
- Grounding techniques (5-4-3-2-1, breathing) for immediate crisis relief

### 👤 Accessible Profile & Privacy Controls
- Language selector for 8 Indian regional languages
- Accessibility toggles: voice-first mode, high contrast, large text, reduced motion
- **ABHA (Ayushman Bharat Health Account)** integration ready
- Granular privacy controls — disable any passive tracking instantly
- One-click data deletion

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML, CSS, Vanilla JS |
| NLP Engine | Rule-based sentiment analysis (IndicBERT architecture reference) |
| On-device ML | TensorFlow Lite (biomarker analysis) |
| AI Development | Built using **Claude (Anthropic)** as primary development tool |
| Deployment | Static — runs in any browser, no server required |

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/your-username/silent-struggles.git

# Navigate into the project
cd silent-struggles

# Open directly in browser — no build step required
open index.html
```

That's it. No npm install, no server, no dependencies. Opens in any browser.

---

## 📁 Project Structure

```
silent-struggles/
│
├── index.html      # Complete app — all features in one file
├── README.md                 # This file
└── assets/                   # (optional) screenshots, demo images
```

---

## 🎯 Who Is This For?

| Group | Key Challenges Addressed |
|---|---|
| 🌸 Women | Postpartum depression, domestic stress, societal stigma |
| 🧓 Elderly | Loneliness, cognitive decline, limited digital literacy |
| 🦽 Disabled | Chronic distress, mobility-related depression, systemic exclusion |

---

## 📸 Screenshots

<img width="1917" height="868" alt="Screenshot 2026-07-30 182910" src="https://github.com/user-attachments/assets/d87fe74d-d8c8-4e85-a087-33381eb71ec6" />
<img width="1917" height="867" alt="Screenshot 2026-07-30 182902" src="https://github.com/user-attachments/assets/9448d955-94de-4de6-a35d-9cc07b0d2c58" />
<img width="1917" height="867" alt="Screenshot 2026-07-30 182851" src="https://github.com/user-attachments/assets/80e146bd-1649-416d-863d-ae53335d5366" />
<img width="1917" height="865" alt="Screenshot 2026-07-30 182919" src="https://github.com/user-attachments/assets/a56983eb-1ec4-44f9-9ece-d99ea237ae63" />

---

## 🔒 Privacy First

- All biomarker analysis is **on-device only** — no raw data ever leaves the user's phone
- Users can disable any passive tracking at any time from the Profile page
- Anonymous peer posting — no real identity required anywhere in the app
- Full data deletion available on request

---

## 🌐 Alignment with National Policy

- **National Mental Health Policy 2014** — preventive, community-based care model
- **Ayushman Bharat Digital Health Mission** — ABHA integration ready
- **iCall & NIMHANS** — direct government infrastructure connection for crisis escalation



## 🙏 Acknowledgements

- **iCall (TISS Mumbai)** — for their real helpline infrastructure
- **NIMHANS** — India's premier mental health institution
- **Vandrevala Foundation** — for free 24/7 crisis support across India
- **Anthropic Claude** — used as the primary AI development tool to build this project



---

<div align="center">
  <b>Every silence has a story. It's time we started listening. 💜</b>
  <br><br>
  Built with ❤️ for India's most vulnerable
</div>
