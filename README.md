# 🧠 ADHD Focus Helper

A collection of practical, low-friction tools and tutorials for people with ADHD, executive dysfunction, task paralysis, and focus challenges.

> Educational resource only. This project is not medical advice and does not replace professional care.

---

# 🎯 What You'll Learn

This repository teaches you how to build ADHD-friendly productivity tools using only HTML, CSS, and JavaScript.

## Included Guides

### ⏰ Standalone Pomodoro Timer
Learn how to build:
- 25/5 Pomodoro timer
- Custom work and break durations
- Audio notifications
- Progress indicators
- Local storage settings
- Mobile-friendly design

### 🌧️ White Noise Generator
Learn how to create:
- White noise
- Pink noise
- Brown noise
- Rain ambience
- Focus soundscapes
- Volume controls

### 📝 Task Capture Tools
Build low-friction task systems designed for ADHD minds.

### 🎯 Focus Sessions
Create distraction-reduced work environments.

---

# ⏰ Building a Standalone Pomodoro Timer

## Why It Helps

Many people with ADHD experience:

- Time blindness
- Difficulty starting tasks
- Hyperfocus without breaks
- Overwhelm from large projects

A Pomodoro timer breaks work into small, visible chunks.

## Basic Structure

```html
<div class="timer">
  <h1 id="time">25:00</h1>
  <button id="start">Start</button>
  <button id="pause">Pause</button>
  <button id="reset">Reset</button>
</div>
```

## Timer Logic

```javascript
let seconds = 1500;

setInterval(() => {
  seconds--;
}, 1000);
```

## Helpful ADHD Features

- Large countdown display
- Progress ring
- Gentle audio alerts
- Session statistics
- Automatic break reminders
- Dark mode

---

# 🌧️ Building White Noise in HTML

## Why White Noise Helps

Some people with ADHD find consistent background sound helpful because it can:

- Reduce distracting noises
- Improve focus
- Mask environmental interruptions
- Create predictable sensory input

Results vary by individual.

## Web Audio API

Modern browsers can generate sound without downloading audio files.

### Basic White Noise Generator

```javascript
const audioCtx = new AudioContext();
const buffer = audioCtx.createBuffer(
  1,
  audioCtx.sampleRate * 2,
  audioCtx.sampleRate
);
```

### Volume Control

```html
<input type="range" min="0" max="100">
```

### Useful Presets

- Rain
- Coffee Shop
- Brown Noise
- Pink Noise
- Fan Sound
- Ocean Waves

---

# 📚 ADHD-Friendly Design Principles

## Typography

Recommended fonts:

- OpenDyslexic
- Atkinson Hyperlegible
- Lexend
- Inter

Example:

```css
body {
  font-family: 'Lexend', sans-serif;
  line-height: 1.8;
}
```

## Visual Design

- Large buttons
- High contrast
- Minimal clutter
- Consistent spacing
- Clear navigation

## Accessibility

- Keyboard navigation
- Screen reader support
- Adjustable font sizes
- Reduced motion options

---

# 🚀 Future Ideas

- Body doubling timer
- Focus music generator
- Habit tracker
- Dopamine menu
- Visual countdown clocks
- Study sprint tracker
- ADHD dashboard
- Executive function toolkit

---

# 🤝 Contributions Welcome

Whether you improve a sentence, fix a typo, add a feature, or share a resource, your contribution matters.

---

## 🌐 Created by OCXLY

Building practical tools for focus, learning, accessibility, and human-centered technology.