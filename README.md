# 🟩 The One Protocol — Project: Wake Up

**A Matrix-inspired interactive browser terminal built as a solo, AI-assisted two-hour hackathon prototype in November 2025.**

The One Protocol is a playful terminal-style experience that combines a branching sequence of commands, animated digital rain, synthesized sound, and spoken feedback.

**[🏆 Devpost project](https://devpost.com/software/project-wake-up) · [📂 Source code](https://github.com/Veloce5/the-one-protocol)**

> **Project context:** This was a short hackathon prototype created with substantial AI coding assistance. It is not presented as a production application. Any external demo link should be verified before being treated as an official deployment of this repository.

## Features

- **Interactive story:** Progress through a sequence of terminal prompts using typed commands.
- **Digital rain:** Canvas-based animated text and retro CRT-inspired styling.
- **Audio:** Tone.js sound synthesis and Web Speech API text-to-speech.
- **State management:** JavaScript logic for stages, commands, and resetting the experience.
- **Optional persistence:** Firebase integration is included for saving mission reports when configured; the experience can also run locally without cloud saving.

## Built with

- HTML, CSS, and vanilla JavaScript
- HTML5 Canvas
- Tone.js
- Web Speech API
- Firebase / Firestore (optional)

## Run locally

1. Clone this repository:

   ```bash
   git clone https://github.com/Veloce5/the-one-protocol.git
   cd the-one-protocol
   ```

2. Open `index.html` in a browser. For browser restrictions affecting local files, use a local development server such as VS Code Live Server.
3. Cloud persistence is optional. Leave Firebase unconfigured to explore the local experience.

## Controls

Type a command into the terminal input and press **Enter**. The prompts guide you through the experience. Use `RESET` to restart.

## Background

This project began with the question: *What would it feel like to interact with a cinematic sci-fi terminal rather than simply watch one?* It was created as a **solo hackathon entry** and used AI-assisted coding to rapidly experiment with animation, audio, and interactive storytelling.

The project is inspired by *The Matrix* and is not affiliated with its creators or rights holders.
