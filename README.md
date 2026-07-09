# 🧠 OCXLY Neuro Lab

> Free, open-source tools for neurodivergent minds.

OCXLY Neuro Lab is a collection of practical, browser-based tools that support
focus, executive function, sensory regulation, and wellbeing. Every tool is a
single self-contained page — **no accounts, no tracking, no build step.** Open
it, save it, or host it anywhere.

## 🚀 Quick Start

**Just want to use the tools?**

1. Open [`index.html`](index.html) in any modern browser, **or**
2. If this repo is published with GitHub Pages, visit the hosted site.

That's it — everything runs on your device.

**Want to run it locally from a clone?**

```bash
git clone https://github.com/ocxly/neurodivergent_toolkit.git
cd neurodivergent_toolkit
# Open the homepage directly...
open index.html          # macOS  (use `xdg-open` on Linux, `start` on Windows)
# ...or serve it (nice for testing on your phone on the same network):
python3 -m http.server 8000   # then visit http://localhost:8000
```

No dependencies to install and **zero external requests** — the Lexend font is
self-hosted (`assets/fonts/`), so every tool works fully offline. If the font
file isn't reachable, tools fall back gracefully to your system font.

## 🧰 Tools

| Tool | What it does |
| --- | --- |
| ⏰ [Pomodoro Pro](examples/pomodoro-timer/) | Work/break focus timer with a 2-minute quick start and a gentle chime |
| 🧩 [Task Chunker](examples/task-chunker/) | Breaks a big or vague task into small, checkable steps |
| 🎉 [Dopamine Menu](examples/dopamine-menu/) | Quick, medium, and big rewards, with a surprise-me picker |
| ⚡ [Executive Function Assistant](examples/executive-function-assistant/) | Suggests a small plan based on your energy, stress, and time |
| 🌧️ [White Noise](examples/white-noise/) | Steady background noise generated in the browser |
| 🟤 [Brown Noise](examples/brown-noise/) | Softer, deeper noise — less sharp than white noise |
| 🌬️ [Breathing Tool](examples/breathing-tool/) | Guided box breathing (respects reduced-motion) |
| 🧘 [Grounding Tool](examples/grounding-tool/) | The 5-4-3-2-1 grounding exercise, one sense at a time |

## ♿ Accessibility & design principles

- **Lexend** typography, self-hosted with a system-font fallback (works offline, no tracking)
- High contrast, low clutter, generous spacing
- Full **light / dark** theme with a per-visitor toggle (remembered across tools)
- Keyboard accessible with visible focus outlines
- Respects `prefers-reduced-motion`
- Mobile-friendly, responsive layouts
- Semantic HTML with live regions for status updates

> Build tools that adapt to people — not people who must adapt to tools.

## 🛣️ Roadmap

**Version 2.0**

- 🔤 Accessibility Center
- 📅 Visual Schedule Builder
- 🌸 Pink Noise Generator
- 💾 Shared settings system
- 📊 Energy Budget Planner
- 🧠 Executive Function Dashboard

## 🤝 Contributing

Contributions of any size are genuinely welcome — a typo fix counts. See
[CONTRIBUTING.md](CONTRIBUTING.md) for the (very short) guidelines. If you're
low on energy, even opening an issue to describe an idea is a real help.

## 🏗️ Project structure

```text
index.html                 # Homepage / launcher
assets/
└── fonts/                 # Self-hosted Lexend (woff2) + its OFL license
examples/
├── pomodoro-timer/
├── task-chunker/
├── dopamine-menu/
├── executive-function-assistant/
├── white-noise/
├── brown-noise/
├── breathing-tool/
└── grounding-tool/
```

Each tool lives in its own folder as a standalone `index.html`.

## 💙 Credits

Created and maintained by **OCXLY**. Developed with AI assistance for
documentation, UI/UX ideas, code examples, and accessibility recommendations.
Project direction, curation, testing, and final decisions by OCXLY.

## 📄 License

Project code released under the [MIT License](LICENSE). The bundled **Lexend**
font is © The Lexend Project Authors, used under the
[SIL Open Font License 1.1](assets/fonts/LICENSE-Lexend.txt).

---

> ⚠️ Educational resource only. This project is **not medical advice** and does
> not replace professional care.

⭐ Building the future, one experiment at a time.
