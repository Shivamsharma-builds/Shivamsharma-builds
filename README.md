# ShivamSharma-Dev-DIATM

Full‑stack developer building JavaScript/TypeScript web apps and practical AI integrations. I create end‑to‑end projects (React + Node) with production-oriented tooling and deployable demos, plus smaller learning projects in C++ and static sites.

GitHub: https://github.com/ShivamSharma-Dev-DIATM  
Avatar: https://avatars.githubusercontent.com/u/204150447?v=4

---

## Pinned projects

- AI-Image-analyzer (VisionLab) — AI-powered image analysis platform (Vite + React frontend, Node + Express backend).  
  Repo: https://github.com/ShivamSharma-Dev-DIATM/AI-Image-analyzer

- Jewelry-E-Commerce — Full-stack e‑commerce platform for jewelry sales (frontend + backend).  
  Repo: https://github.com/ShivamSharma-Dev-DIATM/Jewelry-E-Commerce

- jewellery-frontend — Frontend for the jewelry site (deployed on Vercel).  
  Live: https://jewellery-frontend-lyart.vercel.app  
  Repo: https://github.com/ShivamSharma-Dev-DIATM/jewellery-frontend

- jewellery-backend — Small Node backend for the jewelry project (deployed).  
  Live: https://jewellery-backend-bice.vercel.app  
  Repo: https://github.com/ShivamSharma-Dev-DIATM/jewellery-backend

- Hacktopus-Tech-Triran — JavaScript project (event/client project).  
  Repo: https://github.com/ShivamSharma-Dev-DIATM/Hacktopus-Tech-Triran

- Library_Management — C++ library management system (learning/project).  
  Repo: https://github.com/ShivamSharma-Dev-DIATM/Library_Management

- portfolio — Personal portfolio static site (HTML/CSS).  
  Repo: https://github.com/ShivamSharma-Dev-DIATM/portfolio

- weather-main — Small weather demo / static HTML project.  
  Repo: https://github.com/ShivamSharma-Dev-DIATM/weather-main

---

## About my work / focus

I focus on:
- Practical integrations with AI providers (OpenAI, Gemini, OpenRouter/DeepSeek).
- Building full-stack apps with React (Vite) and Node/Express backends.
- Deploying small production-ready demos and learning projects.

My repositories show a mix of production-style apps (deployable front + back), demo sites, and academic/learning code (C++).

---

## How to run the main project (AI-Image-analyzer)

1) Backend
```bash
cd AI-Image-analyzer/backend
npm install
# copy .env.example -> .env and set keys:
# GEMINI_API_KEY, OPENAI_API_KEY, OPENROUTER_API_KEY (optional)
npm run dev        # development (watch)
# or build + start for production:
npm run build
npm start