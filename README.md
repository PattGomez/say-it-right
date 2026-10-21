# 🗣️ Say It Right — English Pronunciation Practice

A tiny, dependency-free web app to practice English pronunciation. Listen to a
native model voice, say the word or phrase out loud, and get instant
word-by-word feedback with a score.

**Built for Spanish speakers learning English** — the curated lists target the
sounds that are hardest for us (`th`, `v` vs `b`, `sh`, `r`/`l`, long vs short
vowels).

## Features

- **Listen** — a native English voice pronounces the model (Web Speech
  `SpeechSynthesis`).
- **Tap & speak** — your voice is transcribed and scored word by word
  (green = right, red = off), using the browser's `SpeechRecognition`.
- **Record me** — record yourself and play it back to compare with the model
  (`MediaRecorder`).
- **4 modes** — Beginner, Intermediate, Advanced curated lists, plus a **Your
  text** box to practice anything you type.
- Animated score ring, per-item IPA + sound tips, keyboard shortcuts
  (`L` = listen, `Space` = speak).

No build step, no dependencies: one `index.html` plus a favicon.

## Run locally

Open `index.html` in your browser:

```sh
open index.html
```

> **Note:** speech recognition (the scoring) works in **Chrome, Edge, or Arc**
> with a microphone and an internet connection. *Listen* and *Record me* work
> everywhere.

## Deploy

Static site — deploys to any static host. On Vercel, import the repo and deploy
with no configuration (framework preset: **Other**, no build command, output =
repo root).
