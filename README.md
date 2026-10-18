# ♻️ Gamified AI Recycle Bin - Frontend

The frontend of **Gamified AI Recycle Bin**, a web application that uses AI to help users sort waste correctly and turns recycling into a game with points and rewards. Built with **React 19**, **TypeScript** and **Vite**.

> 📝 *Edit the Features and Screenshots sections below to match what your app currently does.*

---

## 📌 Overview

Gamified AI Recycle Bin helps users identify and sort their waste with AI assistance and earn points and rewards for doing it right. This repository contains the client-side application, which connects to the backend API (see [Backend](#-backend)).

## ✨ Features

- 🤖 AI-powered waste identification and sorting guidance (e.g., recyclable, organic, hazardous)
- 🎮 Gamification: points, levels and rewards for correct sorting
- 👤 User accounts and profile
- 📊 Activity history / progress tracking
- 📱 Responsive design for desktop and mobile

*(Replace or remove items that don't apply to your project.)*

## 🛠️ Tech Stack

| Category | Technology |
|---|---|
| Framework | [React 19](https://react.dev/) |
| Language | [TypeScript](https://www.typescriptlang.org/) |
| Build Tool | [Vite](https://vite.dev/) |
| Linting | ESLint with `typescript-eslint`, `react-hooks` and `react-refresh` plugins |

## 📁 Project Structure

```
gamified-ai-recycle-bin-frontend/
├── public/                  # Static assets
├── src/                     # Application source code
│   └── main.tsx             # App entry point
├── index.html               # HTML entry file
├── eslint.config.js         # ESLint configuration
├── tsconfig.json            # TypeScript project references
├── tsconfig.app.json        # TypeScript config for app code
├── tsconfig.node.json       # TypeScript config for Vite config
├── vite.config.ts           # Vite configuration
└── package.json             # Dependencies and scripts
```

## ⚙️ Prerequisites

- [Node.js](https://nodejs.org/) (v20.19+ or v22.12+ recommended for Vite 7)
- npm (comes with Node.js)

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/gamified-ai-recycle-bin-frontend.git
   cd gamified-ai-recycle-bin-frontend
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```
   Open the URL shown in the terminal (usually `http://localhost:5173`).

## 📜 Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start the development server with hot reload |
| `npm run build` | Type-check and create a production build in `dist/` |
| `npm run preview` | Preview the production build locally |
| `npm run lint` | Run ESLint across the project |

## 🔐 Environment Variables

If your app talks to a backend, create a `.env` file in the project root:

```env
VITE_API_BASE_URL=http://localhost:8080
```

<img width="864" height="1232" alt="image" src="https://github.com/user-attachments/assets/e7e5e477-d272-403a-a2af-113c579af9ce" />

🌱 Sort smart. Earn rewards. Help the planet.
