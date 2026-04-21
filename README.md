# Subasri's Digital Canvas 🎨

Welcome to the digital portfolio and personal website of **Subasri R** — an AI Enthusiast, B.E. CSE 2026 student, and future Software Engineer passionate aboi nee dut building human-first technology.

## 🌟 Overview

This project is a premium, highly interactive personal portfolio built to showcase Subasri's skills, projects (spanning AI, IoT, and software development), certifications, and professional experience. The application features a modern, responsive design with smooth animations, custom cursors, and an integrated chatbot.

## 🛠️ Technology Stack

The portfolio is built using modern front-end web technologies for maximum performance and maintainability:

*   **Core Framework**: React 19
*   **Routing & SSR**: [TanStack Start](https://tanstack.com/start/latest) & [TanStack Router](https://tanstack.com/router/latest)
*   **Build Tool**: Vite
*   **Styling**: Tailwind CSS v4 (with custom typography & animations)
*   **UI Components**: [Radix UI](https://www.radix-ui.com/) Primitives
*   **Animations**: Framer Motion
*   **Icons**: Lucide React
*   **Forms**: React Hook Form with Zod validation
*   **Carousels & Sliders**: Embla Carousel React

## ✨ Key Features

The portfolio contains numerous thoughtfully designed sections and generic components:

*   **Interactive UI**: Custom `CursorGlow`, global `Loader`, and a `ScrollProgress` indicator.
*   **Hero Section**: An engaging introduction with a high-impact design.
*   **About Me**: Details about Subasri's background, education, and passions.
*   **Skills Matrix**: A categorically organized showcase of technical skills.
*   **Projects Gallery**: Detailed case studies of AI projects, IoT systems, and software developments.
*   **Experience & Certifications**: Timelines denoting professional achievements and educational milestones.
*   **Contact & Chatbot**: A fully functional contact form combined with a floating AI chatbot for quick inquiries.
*   **Floating Socials**: Quick access to LinkedIn, GitHub, and email from anywhere on the page.

## 🚀 Getting Started

Follow these steps to run the project locally on your machine:

### Prerequisites

*   **Node.js**: Verify that you are running Node version 22.12.0 or higher.
*   **NPM / NPX**: Installed alongside Node.js.

### Installation

1.  Clone the repository or extract the project files.
2.  Open your terminal and navigate to the root directory of the project:
    ```bash
    cd path/to/subasri-s-digital-canvas-main
    ```
3.  Install the dependencies using npm:
    ```bash
    npm install
    ```

### Running the Development Server

1.  Start the development server:
    ```bash
    npm run dev
    ```
2.  Open your browser and navigate to the Localhost URL provided in the terminal (usually `http://localhost:5173`).

### Building for Production

To create an optimized production build, run:
```bash
npm run build
```

## 📁 Project Structure

*   `src/components/portfolio/`: Contains all modular React components broken down by sections (`Hero`, `About`, `Skills`, etc.) as well as reusable UI widgets (`Navbar`, `Chatbot`, `Loader`).
*   `src/routes/`: Houses the TanStack Router routing files (`__root.tsx`, `index.tsx`). Page metadata, configurations, and layout structures are defined here.
*   `src/lib/`: General helper functions and utilities (e.g., classname mergers using `clsx` and `tailwind-merge`).
*   `src/hooks/`: Custom React hooks that manage business logic (e.g., handling mobile responsiveness).
*   `public/`: Contains static assets directly served by the app, such as `Subasri_R_Resume.pdf`.

## 🤝 Contact / Hire Me

I am currently looking for Internships and SDE / AI roles. Feel free to connect or view my online endpoints via the floating socials on the live website.

## 📄 License

This project is open-source and free to use for inspirational purposes.
