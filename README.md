# 💻 Code Debt Tracker

**Code Debt Tracker** is a fun productivity accountability platform built with Angular and Firebase. It helps a group of friends stay consistent by solving at least **one HackerRank problem every day**. If someone misses a day, a fine is added to their "debt." At the end of the month, they settle what they owe.

> 💸 You code. Or you owe.  
> 🔥 Consistency is king.

---

## 🎯 Purpose

This app is designed to:
- Motivate consistent daily practice on HackerRank
- Add fun, peer-driven pressure using small financial penalties
- Track personal growth and competition with streaks and leaderboards
- Promote healthy habit-building as a team

---

## 🧩 Features

- ✅ Email/password registration & login (Firebase Auth)
- 📅 Daily check-in to record solved problems
- 🧮 Automatic fine tracking for missed days (e.g., R10 per day)
- 🏆 Leaderboard (sorted by streaks, problems solved, or least debt)
- 👤 Profile dashboard with personal stats
- 🔔 Daily reminders and toasts (coming soon)
- 💰 Payment status tracking (manual or future SnapScan integration)

---

## ⚙️ Tech Stack

| Layer       | Technology               |
|-------------|---------------------------|
| Frontend    | Angular 17, TailwindCSS  |
| Backend     | Firebase (Firestore, Auth) |
| Hosting     | Firebase Hosting / Vercel |
| Styling     | TailwindCSS              |
| Deployment  | GitHub + Firebase CLI    |

---

## 🚀 Getting Started

### Prerequisites

- Node.js 18+
- Angular CLI (`npm install -g @angular/cli`)
- Firebase CLI (`npm install -g firebase-tools`)
- A Firebase project ([firebase.google.com](https://firebase.google.com))

---

### 1. Clone the Repository

```bash
git clone https://github.com/Solomon-Moyo756/CodeDebtTracker.git
cd code-debt-tracker
npm install
