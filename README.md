<div align="center">
  
  <h1 align="center">🛡️ CYBER.DEV | Portfolio</h1>

  <p align="center">
    <strong>Secure Systems. Scalable Architecture. Premium Design.</strong>
  </p>

  <p align="center">
    <a href="https://react.dev/">
      <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React" />
    </a>
    <a href="https://vitejs.dev/">
      <img src="https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
    </a>
    <a href="https://www.typescriptlang.org/">
      <img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
    </a>
    <a href="https://tailwindcss.com/">
      <img src="https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="TailwindCSS" />
    </a>
    <a href="https://expressjs.com/">
      <img src="https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB" alt="Express.js" />
    </a>
  </p>
</div>

---

## 🚀 Overview

**Cyber.Dev** is a next-generation portfolio website built for security professionals and full-stack developers. It abandons traditional, flat designs for a **immersive, cyber-aesthetic experience** featuring:
-   **Glassmorphism & Neon Glitch Effects**
-   **Interactive Terminal Aesthetics**
-   **End-to-End Type Safety**
-   **Responsive Mobile-First Architecture**

## ✨ Key Features

-   **Cyberpunk UI**: Custom Tailwind configuration for neon glows, matrix-like typography, and dark-mode optimization.
-   **Live GitHub Activity**: Integrated `react-github-calendar` to visualize coding streaks.
-   **Interactive Terminal**: A `framer-motion` powered CLI simulation showcasing security methodologies.
-   **Secure Contact Form**: Decoupled Express.js backend for secure email handling via Resend API.
-   **Project Spotlight**: Dynamic spotlight hover effects on project cards.
-   **Optimized Performance**: Migrated from Next.js (SSR) to Vite (SPA) for lightning-fast client-side navigation.

## 🛠️ Tech Stack

### Frontend
-   **Core**: React 18, Vite 5, TypeScript
-   **Styling**: Tailwind CSS v3, PostCSS, Lucide React (Icons)
-   **Animation**: Framer Motion (Page transitions, Scroll reveal, Hover effects)
-   **Utils**: `clsx`, `tailwind-merge`

### Backend
-   **Server**: Node.js, Express.js
-   **Email Service**: Resend API
-   **Security**: `cors`, `dotenv`

## 🏁 Getting Started

### Prerequisites
-   Node.js (v18+)
-   npm or yarn

### Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/your-username/cyber-portfolio.git
    cd cyber-portfolio
    ```

2.  **Install Dependencies**
    ```bash
    npm install
    ```

3.  **Environment Setup**
    Create a `.env.local` file in the root directory:
    ```env
    # Frontend (Vite)
    VITE_API_URL=http://localhost:3001
    
    # Backend (Express / Server)
    RESEND_API_KEY=re_123456789
    EMAIL_TO=your-email@example.com
    ```

### Running Locally

This project runs the Frontend and Backend separately.

**Terminal 1: Frontend**
```bash
npm run dev
# Running on http://localhost:5173
```

**Terminal 2: Backend**
```bash
npm run server
# Running on http://localhost:3001
```

## 🚢 Deployment

### Frontend (Vercel/Netlify)
Run the build command to generate a static `dist` folder:
```bash
npm run build
```
Deploy the `dist/` folder. Ensure you set `VITE_API_URL` to your production backend URL.

### Backend (Render/Vercel/Heroku)
Deploy the `server/` directory as a Node.js web service.
-   **Command**: `node index.ts` (or `node server.js` if compiled)
-   **Env Vars**: `RESEND_API_KEY`, `EMAIL_TO`

## 📂 Project Structure

```
├── src/
│   ├── components/     # UI & Section Components
│   ├── data/          # Static content (Portfolio Data)
│   ├── lib/           # Utilities & Animations
│   ├── App.tsx        # Main Component Router
│   └── main.tsx       # Entry Point
├── server/            # Express Backend
├── dist/              # Production Build
└── index.html         # Vite Entry HTML
```

---

<p align="center">
  Built with 💚 and strict types by <a href="https://github.com/TheAmazingDeveloper">TheAmazingDeveloper</a>
</p>
