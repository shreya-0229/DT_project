# ThinkFirst — AI Learning Companion

A Design Thinking project prototype by **Shreya Gaikwad (125B1B020)** & **Anjali Kadam (125B1B021)**
Pimpri Chinchwad College of Engineering (PCCOE) — Second Year, Computer Engineering

> *"Use AI to enhance your learning, not replace your thinking."*

## The Problem

Students increasingly use Generative AI for assignments, coding, explanations, summaries and exam preparation. Because AI gives a ready-made answer in seconds, students often:

- Copy solutions without fully understanding them
- Rarely attempt a problem independently first
- Develop reduced independent problem-solving skills
- Have no awareness of how much they rely on AI

Students struggle to distinguish **useful assistance** from **overdependence that reduces learning**.

## Our Solution

**ThinkFirst** is an AI Learning Companion that works like a guide, not an answer machine. AI help comes *after* the student's own thinking — through hints, questions and tracking — so learning stays with the student.

## Features

1. **Student Dashboard** — AI Dependency Score, independent attempts, AI asks, learning streak, and the balance between AI-assisted and independent learning
2. **Hint-First AI Assistance** — Hint 1 → Hint 2 → Hint 3; the full step-by-step explanation stays locked until the student submits their own attempt
3. **Independent Attempt Mode** — timed attempt with personalised feedback on what was correct and what was missing
4. **Concept-Based Learning** — concepts explained in simple steps with analogies and an "Explain like I'm 15" version
5. **Audio Explanations** — Listen / Pause / Stop narration of concept explanations with a synced transcript and speed control
6. **YouTube Suggestions** — "Watch & Clear This Concept" video suggestions for every concept, with topic search and filters
7. **Socratic (Learning) Mode** — the AI asks guiding questions first and encourages the student to think before giving assistance
8. **AI Usage Tracker** — AI usage frequency, task-wise breakdown, dependency trend and overuse warnings
9. **Google Classroom Sync** — imports courses and assignments; each assignment can be started in Hint-First or Attempt-First mode
10. **Check Your Understanding** — a 3-question quiz after a concept, with instant marking
11. **Reflection** — end-of-session reflection on what was learned without AI, with weak-area suggestions

Every action updates the shared AI Dependency Score, so students can *see* their dependence go down as their independent learning goes up.

## How to Run

This is a single-file web prototype — no build step, no server, no API keys needed.

- **Option 1:** Download `index.html` and open it in any modern browser (Chrome recommended for the audio narration).
- **Option 2 (GitHub Pages):** In this repository, go to **Settings → Pages**, set Source to **Deploy from a branch → main → / (root)**, and open the published link.

## Tech

HTML, CSS and JavaScript in one self-contained `index.html` file. All features run live in the browser; the sample learning data is illustrative and the Google Classroom sync is a prototype flow with sample classroom data.

## Expected Impact

- Encourages independent thinking
- Improves conceptual understanding
- Develops problem-solving skills
- Reduces blind dependence on AI-generated answers
- Promotes responsible use of Generative AI
