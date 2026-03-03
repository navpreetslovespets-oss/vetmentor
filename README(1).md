# VetMentor — Veterinary Clinical Training Platform

> AI-powered clinical training for veterinary professionals at Supertails.

## Quick Start

1. **Get a free Gemini API key** from [aistudio.google.com/apikey](https://aistudio.google.com/apikey)
2. **Open the app** at your GitHub Pages URL
3. **Login** with a demo account (shown on login screen)
4. **Click the 🔑 icon** in the top bar and paste your Gemini API key
5. Start learning!

## Demo Accounts

| Email | Password | Role |
|---|---|---|
| priya@supertails.com | vet123 | Vet |
| arjun@supertails.com | vet123 | Vet |
| navpreet@supertails.com | admin123 | Admin |

## Features

- **Socratic Case Discussions** — AI-guided clinical reasoning with 8 seed cases
- **MCQ Assessments** — Ettinger-referenced quizzes with detailed explanations
- **AI Content Generator** — Admins can generate new cases & questions
- **Case Feed** — Share real clinical cases across clinics
- **Progress Tracking** — Topic performance, quiz history, activity log
- **Admin Dashboard** — Monitor all vets' training progress

## Rate Limiting

Each user gets **30 AI calls per day** (resets at midnight). This prevents runaway API costs on the free Gemini tier. Usage is tracked per-user in localStorage.

## Deploy to GitHub Pages

1. Create a new GitHub repository
2. Upload `index.html` to the repo
3. Go to **Settings → Pages → Source → Deploy from branch (main)**
4. Your app will be live at `https://yourusername.github.io/repo-name/`

## Tech Stack

- React 18 (via CDN)
- Google Gemini 2.0 Flash API (free tier)
- localStorage for persistence
- Zero backend — runs entirely in the browser

## API Key Security

Your Gemini API key is stored **only in your browser's localStorage**. It is never sent to any server except Google's Generative AI API endpoint. Each user needs their own key.
