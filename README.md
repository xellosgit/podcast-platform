# AI Podcast Platform

Welcome to the **AI Podcast Platform**, a cutting-edge SaaS application that revolutionizes podcast creation and discovery. Powered by AI-driven text-to-speech, dynamic podcast generation, and seamless playback, this platform enables users to create, listen, and explore podcasts effortlessly.

## 🤖 Introduction

The **AI Podcast Platform** is a feature-rich application that leverages artificial intelligence to empower creators and listeners alike. It includes **text-to-audio conversion** with multiple AI-generated voices, **automated podcast thumbnail generation**, and a **seamless listening experience** through a sticky podcast player.

Looking for assistance? Join our **Discord community (34k+ members)** where developers support each other and share insights.

---

## ⚙️ Tech Stack

This project utilizes modern web technologies to ensure scalability, performance, and an excellent user experience:

- **Next.js** – Framework for React-based applications
- **TypeScript** – Strongly typed JavaScript for better development
- **Convex** – Data storage and backend logic
- **OpenAI** – AI-driven text-to-speech and content generation
- **Clerk** – Authentication and user management
- **ShadCN** – UI components for an elegant design
- **Tailwind CSS** – Utility-first styling framework

---

## 🔋 Features

The platform comes with a rich set of features, including:

✔ **Secure Authentication** – User sign-in and sign-up with Clerk authentication.
✔ **Modern Home Page** – Showcases trending podcasts with a persistent podcast player.
✔ **Podcast Discovery** – Browse and explore new and trending podcasts.
✔ **Full-Text Search** – Quickly find podcasts using advanced filtering.
✔ **AI-Powered Podcast Creation** – Convert text to audio with multi-voice AI.
✔ **Podcast Thumbnail Generation** – Automatic AI-generated thumbnails for podcasts.
✔ **User Profile Management** – View and manage all created podcasts.
✔ **Podcast Details Page** – Displays in-depth information including transcript and listener count.
✔ **Advanced Podcast Player** – Includes playback controls and mute/unmute functionality.
✔ **Responsive Design** – Fully optimized for all screen sizes.
✔ **Scalable Code Architecture** – Designed for maintainability and reusability.

---

## 🕸️ Snippets (Code to Copy)

Some key files and directories for quick reference:

- **Global Styles**: `app/globals.css`
- **Tailwind Configuration**: `tailwind.config.ts`
- **Constants**: `constants/index.ts`
- **Backend API (Convex)**:
  - `convex/http.ts`
  - `convex/users.ts`
  - `convex/podcasts.ts`
- **Reusable Components**:
  - `components/PodcastDetailPlayer.ts`
  - `components/PodcastPlayer.ts`
  - `components/ProfileCard.tsx`
- **Utility Functions**:
  - `lib/formatTime.ts`
  - `lib/useDebounce.ts`
- **Profile Page**: `profile/[profileId]/page.tsx`

