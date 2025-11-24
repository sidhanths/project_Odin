Sidhanth Pro OS 🚀

A private, cross-platform Life Operating System for high-performance tracking (Habits, Study, Gym).
Syncs real-time between Laptop (Web), Mobile, and Apple Watch.

🏗 System Architecture

Frontend: HTML5, TailwindCSS, Alpine.js (Single File, No Build Step).

Backend: Firebase Firestore (Cloud Sync).

Edge: Scriptable (iOS/WatchOS Widget).

Hosting: Netlify / Vercel.

🛠 Setup Instructions

1. Web Dashboard (Laptop/Mobile)

Create a Firebase Project at console.firebase.google.com.

Create a Firestore Database (Start in Test Mode).

Copy your firebaseConfig keys.

Paste keys into index.html (lines 16-25).

Deploy index.html to Netlify/Vercel (Drag & Drop).

Login: admin (Change in code line ~320).

2. Apple Watch / iOS Widget

Install Scriptable app on iPhone.

Create a new script and paste the code from widget.js.

Add Scriptable Widget to iOS Home Screen.

For Watch: Create an iOS Shortcut: Run Script (Sidhanth Pro) -> Show Notification.

🖥 Usage

Midnight Reset: Tasks auto-uncheck at 12:00 AM local time.

Streak Logic: Auto-increments if opened on a new day.

Confetti: Triggers on task completion; Massive burst at 100%.

🔒 Security

Client-side password protection (Default: admin).

Firestore Rules: Currently open (Test Mode). Lock down for production.
