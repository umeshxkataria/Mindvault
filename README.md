# Mindvault
# 🧠 MindVault — Journal Your Emotions, Track Your Moods

MindVault is a minimalistic journaling web app that lets you capture your thoughts, track your mood, and gain AI-powered reflections over time. Designed with mental wellness in mind, it combines simplicity with emotional intelligence.

## 🔗 Live Demo
👉 [Visit MindVault](https://mindvault-kohl.vercel.app/)

---

## ✨ Features

- 📝 **Thought Logging** – Journal freely and let MindVault analyze your tone.
- 🎭 **Mood Detection** – Auto-categorizes your mood using sentiment analysis & keyword mapping.
- 🌈 **Visual Gradients** – Dynamic mood-based UI gradients to reflect your inner world.
- 📊 **Mood Insights (Coming Soon)** – Track emotional patterns over days/weeks.
- 🤖 **AI Reflections (Upcoming)** – Generate gentle reflections based on your entries.
- ☁️ **Cloud Sync with Firebase** – Your thoughts, always backed up and accessible.

---

## 🛠️ Tech Stack

- **Frontend**: React, Tailwind CSS, Framer Motion
- **Backend**: Firebase Auth, Firestore Database
- **NLP & AI**: OpenAI (planned), Natural Language Sentiment API
- **Hosting**: Vercel

---

## 📁 Project Structure

```bash
mindvault/
├── components/         # Reusable UI components
├── lib/                # Utility functions (auth, mood detection, etc.)
├── pages/              # Route-based components
├── public/             # Static assets
├── styles/             # Tailwind & global styles
├── firebase.js         # Firebase initialization
└── .env.local          # Environment variables (API keys, etc.)


##🔧 Setup Instructions

Clone the Repository

**#bash**
Copy
Edit
git clone https://github.com/yourusername/mindvault.git
cd mindvault
Install Dependencies

**#bash**
Copy
Edit
npm install
Configure Firebase

Create a Firebase project.

Enable Google Auth and Firestore.

Add your credentials to .env.local:

ini
Copy
Edit
NEXT_PUBLIC_FIREBASE_API_KEY=xxx
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=xxx
NEXT_PUBLIC_FIREBASE_PROJECT_ID=xxx
Run Locally

bash
Copy
Edit
npm run dev
🤯 What Inspired This?
Mental health is often overlooked in our fast-paced lives. MindVault was built during the CodeCircuit Hackathon to create a safe, personal, and insightful space for self-reflection—no noise, no distractions, just you and your thoughts.

📌 Roadmap
 Google Authentication 
 Thought journaling with mood detection
 Mood-based gradients
 AI-powered reflections
 Mood analytics dashboard
 Mobile push reminders
 Export thoughts as PDF

🤝 Contributing
Contributions are welcome! Open issues or PRs for features, bugs, or enhancements.

🧑‍💻 Author
Made with ❤️ by Umesh
“Your thoughts deserve a vault — one that listens, understands, and grows with you.”
