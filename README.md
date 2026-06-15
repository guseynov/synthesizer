# Synthesizer

A compact browser synthesizer built with React, Vite, and Tone.js.

## What it does

- Play notes with your mouse, touch, or computer keyboard
- Switch between multiple synth engines
- Stack live audio effects like reverb, chorus, delay, phaser, and more
- Shift octaves with the on-screen controls or arrow keys

## Tech Stack

- React 19
- Vite
- TypeScript
- Tone.js
- Sass

## Getting Started

Install dependencies:

```bash
npm install
```

Run the development server:

```bash
npm run dev
```

Build for production:

```bash
npm run build
```

Preview the production build locally:

```bash
npm run preview
```

## Controls

- Mouse or touch: click piano keys to play notes
- Keyboard: use `A` through `;` for the visible range
- Octave shift: `ArrowUp` and `ArrowDown`
- Instrument: choose a synth type from the dropdown
- Effects: toggle the audio effects panel on and off

## Notes

- Audio starts only after the first user interaction because browsers block autoplay.
- The keyboard spans two octaves and updates as you change the base octave.

## Project Structure

- `src/App.tsx` - main synthesizer logic and UI
- `src/components/` - reusable controls and piano key components
- `public/` - static assets such as `manifest.json` and `robots.txt`

