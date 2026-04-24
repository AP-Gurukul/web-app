# AP-Gurukul Web App

This is the student-facing Next.js application for the AP-Gurukul platform.

## 🔄 Universal Data Sync & Authentication
**This application shares a unified Firebase database with the entire AP-Gurukul ecosystem.** 
- Users authenticate via **Gmail (Google Auth)**. If a user logs into this Web App with their Gmail account, their profile, progress, and history are perfectly synced. They can open the AP-Gurukul Mobile App or Telegram App using that same Gmail account and seamlessly resume their session!
- If an admin updates course content, uploads a DOCX file of new questions, or changes permissions in the Admin Portal, those changes instantly reflect in this Web App in real-time.

## 🚀 Getting Started

First, run the development server:
```bash
npm install
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## 🤝 Contributing
Please see the `CONTRIBUTING.md` and `SECURITY.md` files for guidelines. As an open-source contributor, you will test this UI against our public staging APIs.
