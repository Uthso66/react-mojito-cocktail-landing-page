# 🍸 Mojito Cocktail Landing Page — React + GSAP + TypeScript

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge\&logo=react\&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge\&logo=typescript\&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge\&logo=greensock\&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge\&logo=vite\&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge\&logo=vercel\&logoColor=white)

A visually bold, motion-heavy **cocktail landing page** built with **React**, **TypeScript**, and **GSAP**.
This project is where I intentionally went *deep* on motion, timing, and interaction — not just to make things move, but to make them feel right.

Think: smooth, slightly over-engineered animations… on purpose.

👉 **Live Demo**
[View Live Site](https://react-mojito-cocktail-landing-page-i6945mc71-uthsos-projects.vercel.app/)

---

## 🚀 Key Engineering Features (a.k.a. where I went a bit wild)

* 🍃 **GSAP Parallax:** Multi-layered, scroll-driven parallax using leaf elements — because flat UIs are boring.
* ✂️ **Advanced Text Reveal:** `SplitText`-powered word-by-word typography animations (yes, I obsessed over timing).
* 🎥 **Video Scroll-Trigger:** Cinematic video playback tied directly to scroll position for that “whoa” moment.
* 🔄 **Interactive Menu Slider:** Custom React slider with GSAP timelines, overwrite logic, and state sync (no jank allowed).
* 🛡️ **Type Safety:** Fully written in **TypeScript**, so animation refs don’t turn into runtime chaos.
* 📱 **Adaptive Design:** Responsive without sacrificing the premium feel on smaller screens.

---

## 🧱 Tech Stack

| Layer         | Technology                               |
| ------------- | ---------------------------------------- |
| **Frontend**  | React (Hooks, Context)                   |
| **Language**  | TypeScript                               |
| **Animation** | GSAP (ScrollTrigger, SplitText, useGSAP) |
| **Styling**   | Tailwind CSS / CSS Modules               |
| **Bundler**   | Vite                                     |
| **Hosting**   | Vercel                                   |

---

## 🎯 Why This Project Exists (honest version)

I built this project to:

* Push past “basic animations” and into **timeline orchestration**
* Prove I can handle **complex motion + React state** without things falling apart
* Practice writing **TypeScript that actually helps**, especially with animation refs
* Translate high-fidelity, agency-style visuals into clean, readable code

There’s no backend here by design.
This project is about **feel**, **polish**, and **control** — the stuff frontend engineers actually get judged on once the basics are assumed.

---

## 🎞️ Animation & Motion Breakdown (for fellow motion nerds)

The animations aren’t just decoration — they’re doing real work.

### 🟢 Scroll-Driven Storytelling

* **Pinning & Masking:** Sections like *“The Art”* use GSAP pinning to slow the user down and control focus.
* **Scrubbing:** Parallax elements are linked to scroll velocity for a more physical, tactile interaction.

### 🟢 Component Lifecycle Management

* **React Hygiene:** Animations are properly cleaned up using `revert()` / `kill()` to avoid memory leaks.
* **State Sync:** Sliders and timelines stay in sync with React state so interactions remain predictable (even under stress).

---

## 💻 Local Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/Uthso66/react-mojito-cocktail-landing-page.git
cd react-mojito-cocktail-landing-page
```

### 2️⃣ Install dependencies & run

```bash
npm install
npm run dev
```

Runs locally at:
👉 [http://localhost:5173](http://localhost:5173)

---

## 🧪 Notes

* Frontend-focused by intention
* No backend or APIs involved
* Built for modern browsers
* Best viewed as a **motion/UI case study**, not a CRUD app

---

## 🧔 Author

**Uthso**
*Software QA Engineer • Security Enthusiast • AI/ML Hobbyist*

🐙 GitHub: [https://github.com/Uthso66](https://github.com/Uthso66)
💼 LinkedIn: [https://www.linkedin.com/in/tarikul-islam-uthso/](https://www.linkedin.com/in/tarikul-islam-uthso/)

---

## 🪄 License

MIT License © 2025 Uthso

