# Resonara

**Resonara R-1** is a voice and frequency instrument that runs entirely in the browser, in a single file (`index.html`).

## Features

- **Voice analysis**: live fundamental frequency (F₀) detection using the YIN algorithm, a spectrum ring from 60 Hz to 2 kHz, an analogue cents meter, a pitch-stability line and a harmonic profile from H2 to H8.
- **Load file**: analyses an audio recording when a microphone isn't available.
- **Binaural synthesis**: rotary knobs for carrier, beat, pink noise and level; an L×R phase scope; click-free fades and a safety limiter.
- **Presets**: a bank of 12, including Golden Ratio φ, Schumann 7.83, Gamma 40 and Solfeggio tones.
- **Session timer** with automatic fade-out, a screen wake lock and keyboard shortcuts (`Space` play, `M` listen).

## Run it

The page must be served over **HTTPS** (or `http://localhost`) for the microphone to work. Opening the file directly from disk will block the mic.

- **GitHub Pages**: go to *Settings → Pages*, choose *Deploy from a branch*, select `main` and `/ (root)`. The app will then be live at `https://somersetnomad.github.io/-Resonara/`.
- **Locally**: run `python3 -m http.server` in this folder, then open `http://localhost:8000`.

---

Resonara is a sound and relaxation instrument, not a medical device. Audio stays on the user's device.
