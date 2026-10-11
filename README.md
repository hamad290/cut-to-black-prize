# Cut to Black Prize — Frontend

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)  
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](https://github.com/muhammadranju/cut-to-black-prize-frontend/actions)

---

## 📘 Project Overview

**Cut to Black Prize** is a web application that serves as the frontend for a prize-based activity platform. The project allows users to browse prize contests, view details, and (depending on backend support) participate in various prize events. The goal of this frontend is to provide a clean, responsive, and user-friendly experience for contest participants.

**Key features:**

- Responsive design built with **Next.js** and **TypeScript**
- Modular component architecture
- State management using React hooks
- Integration with a backend API (assumed)
- Styled with modern CSS (or CSS modules / Tailwind / etc. — adjust if different)

---

## 🚀 Tech Stack

| Technology                | Purpose                                                     |
| ------------------------- | ----------------------------------------------------------- |
| **Next.js**               | React framework for server-side rendering and static export |
| **TypeScript**            | Type safety and better developer experience                 |
| **React**                 | UI component library                                        |
| **CSS / SCSS / Tailwind** | Styling (adjust to whatever stack you are using)            |
| **Vercel**                | Deployment (based on project URL)                           |

---

## 📁 Folder Structure

Here’s a high-level view of the major directories in this repository:

```

├── public/               # Static assets (images, fonts, etc.)
├── styles/               # CSS or SCSS files
├── components/           # Reusable React components
├── hooks/                # Custom React hooks
├── lib/                  # Utility functions, API clients
├── app/                  # Pages and layout
├── next.config.mjs       # Next.js configuration
├── package.json          # Dependencies and scripts
└── tsconfig.json         # TypeScript configuration

```

---

## 💻 Getting Started

These instructions will help you set up the project locally for development and testing.

1. **Install dependencies**

   ```bash
   npm install
   # or
   bun install
   ```

2. **Environment variables**

   Create a `.env.local` in the root (if needed) with variables like:

   ```
   NEXT_PUBLIC_API_URL=https://your-backend-api.com
   # other env vars ...
   ```

3. **Run in development mode**

   ```bash
   npm run dev
   # or
   bun dev
   ```

   Then open [http://localhost:3000](http://localhost:3000) in your browser.

4. **Build for production**

   ```bash
   npm run build
   npm run start
   # or with bun
   bun build
   bun start
   ```

---

## 📞 Contact / Support

If you have any questions, feedback, or want to report a bug, feel free to:

- Open an **issue** on this GitHub repository
- Reach out to **Hammmad Ur Rehman** — hamad290k@gmail.com
"# cut-to-black-prize-frontend" 

