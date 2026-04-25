# Wasabi Gaming Frontend Client

Welcome to the frontend application of the Wasabi Gaming ecosystem. This application presents a visually rich, engaging, and dynamic interface for users and portfolios.

## 🛠 Tech Stack

- **Framework**: Next.js 14, React 18, TypeScript (fully typed infrastructure)
- **Styling**: TailwindCSS, Ant Design, Radix UI & generic Micro-animations.
- **State Management**: Zustand (for streamlined global state) & React Query (`@tanstack/react-query` for API fetching caches).
- **Authentication**: `next-auth` paired with standard JSON Web Token (JWT) strategies.
- **Interactions**: Canvas Confetti, Embla Carousel, Framer Motion (via tailwindcss-animate).
- **Document Rendering**: Built-in support for rendering UI contexts into documents (`html2canvas`, `jspdf`, `react-to-pdf`).

## 🚀 Architecture & Best Practices

* **Optimized Rendering**: Takes full advantage of Next.js server-side rendering (SSR) and client-side transitions to ensure sub-second page interactivity.
* **UI/UX Aesthetics**: Beautiful interfaces modeled using granular Tailwind utility grids, implementing smooth transitions.
* **Reusable Components**: Separated concerns via `src/components`, `src/hooks`, and `src/layouts` to maximize component scalability and maintainability.

## ⚙️ Getting Started

1. **Ensure Node.js is installed (v18+)**
2. **Install dependencies**:
   ```bash
   npm install
   ```
3. **Set your Environment**:
   Duplicate `.env.example` to `.env.local` and add your required NextAuth secrets, Google Client IDs, and backend API routes.
4. **Run the local dev server**:
   ```bash
   npm run dev
   ```

*Open `http://localhost:3000` with your browser to see the outcome.*
