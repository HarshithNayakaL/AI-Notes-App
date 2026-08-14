# AI Notes — Powered by DeepSeek

**AI Notes** is a modern, elegant, and responsive note-taking web app enhanced with local AI capabilities. Built with pure HTML, CSS, and JavaScript, it integrates with the `deepseek-r1:1.5b` model running via Ollama to bring advanced AI features right into your browser — no external server required.

---

## Description

AI Notes provides a clean, focused interface for writing and organizing notes, powered by artificial intelligence. It allows users to create, edit, delete, and search through notes with ease. The app enhances your writing experience by offering AI-driven tools for summarizing, improving, and expanding your content.

With support for **light/dark modes**, **autosave**, and **AI assistance**, this single-page app is ideal for students, developers, writers, and anyone looking to boost their productivity with the help of local AI.

---

## Design

The interface follows a 2026 Apple-inspired design system:

- Floating glass panels with soft blur, rounded corners, and layered shadows
- A bento-grid layout for the notes list and AI action tiles
- A restrained, poppy accent gradient used sparingly on branding and calls to action
- Fluid, system-font typography with tight tracking on headlines
- Smooth, GPU-friendly transitions (transform and opacity only) with `prefers-reduced-motion` support
- A responsive mobile navigation drawer, since the previous layout simply hid the sidebar with no way to reopen it
- Vector iconography throughout instead of emoji, for a consistent, native feel
- Full light and dark mode support via CSS custom properties

---

## Features

- Light and dark theme toggle
- AI Assistant (powered by DeepSeek R1 via Ollama)
  - Summarize content
  - Improve writing
  - Expand ideas
  - Generate questions
  - Extract keywords
- Create, save, and delete notes
- Real-time search
- Offline storage with `localStorage`
- Responsive, bento-grid UI with smooth animations
- Keyboard shortcuts: `Cmd/Ctrl+S` save, `Cmd/Ctrl+N` new note, `Cmd/Ctrl+D` toggle theme

---

## Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (no frameworks)
- **AI Integration:** [Ollama](https://ollama.com) with `deepseek-r1:1.5b`
- **Data Storage:** Browser LocalStorage
- **Architecture:** Single Page Application (SPA)

---

## Getting Started

### 1. Clone the repository (or download the files)
```bash
git clone https://github.com/Harshith29124/AI-Note-Taking-App.git
cd AI-Note-Taking-App
```

### 2. Set up Ollama and DeepSeek R1
- Install [Ollama](https://ollama.com)
- Pull and run the model:
```bash
ollama pull deepseek-r1:1.5b
ollama run deepseek-r1:1.5b
```

### 3. Run the App
- Open `index5.html` in any browser (Chrome, Edge, Brave, etc.)

---

## Project Structure

```
ai-notes/
├── index5.html     # Main frontend (HTML + CSS + JS)
├── README.md       # Project documentation
```

---

## License

This project is open-source and available under the MIT License.

---

## Author

Made by **Harshith Nayak**
GitHub: [@Harshith29124](https://github.com/Harshith29124)
