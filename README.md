# 🌸 EmotiSense — AI-Powered Emotional Wellness Platform

> *Understand your emotions. Nurture your wellbeing.*

EmotiSense is a fully client-side emotional wellness web application that helps users discover, track, and nurture their emotional state through intelligent quiz analysis, real-time facial recognition, and an empathetic AI companion — all in one beautifully designed interface.

---

## ✨ Features

### 🧠 Dual Emotion Detection
- **Emotion Quiz** — 10 thoughtfully crafted questions with a weighted scoring algorithm across 13 distinct emotion categories
- **Face Analysis** — Real-time AI facial recognition that reads micro-expressions and maps emotional state instantly via your camera

### 💬 Sage — AI Emotional Companion
- Powered by the **Anthropic Claude API**
- Empathetic, non-judgemental conversational support
- Maintains full conversation memory within each session
- Responds with personalised guidance based on your detected emotion

### 📊 Emotion Dashboard
- Visual mood trend chart across your last 7 sessions
- Emotion breakdown with percentage distribution
- Full session history with timestamps and source tracking
- Day streak tracker and session statistics

### 🌿 Wellness Remedies (6 Categories)
| Category | Examples |
|---|---|
| 🫁 Breathing | 4-7-8 Calm Breath, Box Breathing, Ocean Wave |
| 🧘 Meditation | Body Scan, Loving-Kindness, Binaural Sound Bath |
| 📓 Journaling | Emotional Dumping, Gratitude Mapping, Letter to Future Self |
| 🏃 Movement | Mindful Walk, Free-Form Dance, Power Shake |
| 💬 Affirmations | Mirror Work, Emotional Permission, Night Inventory |
| 🍵 Nourishment | Chamomile Tea, Dark Chocolate Ritual, Golden Milk Elixir |

### 👤 User Profiles & Authentication
- Secure registration and login with email/password
- Persistent user data stored in localStorage
- Editable profile with bio, name, and wellness summary
- Emotional wellbeing score based on recent session history

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript (no frameworks) |
| AI Companion | Anthropic Claude API (`claude-sonnet-4-20250514`) |
| Storage | Browser localStorage |
| Fonts | Google Fonts — Playfair Display + Nunito |
| Auth | Custom implementation with Base64 password encoding |

---

## 📁 Project Structure

```
emotisense/
│
├── emotion_quiz.html       # Main app — quiz, dashboard, chat, profile, remedies
└── emotion_face.html       # Face analysis module (AI facial recognition)
```

---

