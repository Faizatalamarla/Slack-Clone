# Slack Clone – Team Messaging Platform

A modern, scalable team communication platform inspired by Slack. Built using Next.js, TypeScript, Tailwind CSS, and Firebase, this project offers real-time messaging, workspace and channel management, file uploads, and video calls in a sleek, responsive UI.

> This is a full-stack project ideal for learning architecture patterns, authentication, WebSocket communication, and real-world app design.

---

## ✨ Key Features

- 🔐 Secure authentication with email and third-party providers
- 💬 Real-time group and direct messaging
- 🧑‍🤝‍🧑 Workspace and channel creation
- 📁 File sharing and rich text support
- 📹 Embedded video chat
- ⚙️ Modern UI built with Tailwind and Radix components

---

## 🧱 Tech Stack

| Layer        | Technology                 |
|--------------|-----------------------------|
| Frontend     | Next.js 14, TypeScript, Tailwind CSS |
| Backend/API  | Next.js API Routes, Firebase |
| Auth         | Firebase Auth               |
| Database     | Firebase Firestore          |
| Video Calls  | LiveKit                     |
| Uploads      | UploadThing                 |
| UI Library   | shadcn/ui, Headless UI      |

---

## 🛠 Setup Instructions

1. **Clone the repository**

```bash
git clone https://github.com/your-username/slack-clone.git
cd slack-clone
```

2. **Install dependencies**
```bash
npm install
```
3. **Set up Firebase**
   Create a .env file using .env.example:
```bash
NEXT_PUBLIC_FIREBASE_API_KEY=your_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
...

```
2. **Start the development server**
```bash
npm run dev

```
---

## 🚀 Project Structure
```src/
├── app/                  # App routing (Next.js 14)
├── components/           # UI components and dialogs
├── actions/              # Business logic and Firebase operations
├── styles/               # Tailwind and global styles
├── middleware.ts         # Middleware logic
```

---

## 🧪 Scripts

npm run dev – Run in dev mode

npm run build – Compile for production

npm run lint – Run ESLint

npm run type-check – TypeScript validation

---

## 🤝 Contribution Guidelines

We welcome contributions!

Fork this repository

Create a feature branch

Submit a Pull Request

See CONTRIBUTING.md for full guidelines.

---

## 🛡 License

Distributed under the MIT License. See LICENSE for more information.


