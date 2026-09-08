# DualWave 🌊🎮

An expressive motion synthesizer and continuous lead instrument playable with a **PlayStation 5 DualSense controller** (via WebHID or Gamepad API), **Touch Ribbon**, and **Computer Keyboard**.

---

## 🌟 Live Demo

👉 **[https://grandsummoner.github.io/dualwave/](https://grandsummoner.github.io/dualwave/)**

> **Browser Requirement for DualSense Controller:** Use Google Chrome, Microsoft Edge, or any Chromium-based desktop browser for full **WebHID** gyro motion and touch-pad support over HTTPS.

---

## 🎹 Features

- **PS5 DualSense Motion Control:**
  - **Gyro & Accelerometer:** Pitch and tilt the controller to glide pitch and control vibrato like a digital Theremin.
  - **Analog Triggers (L2/R2):** Smooth volume and dynamics control with adaptive trigger resistance.
  - **Haptic & Lightbar Feedback:** Real-time LED colors match current pitch and musical root.
  - **DualSense Touchpad:** Multi-touch X/Y filter sweeps (Cutoff & Resonance).
- **Virtual Touch Ribbon:** Full continuous pitch surface with microtonal readout, scale snapping, and glide options.
- **Rich Synthesizer Engine:**
  - Multi-waveform oscillator (Sine, Triangle, Sawtooth, Square).
  - Resonant low-pass filter with envelope modulation.
  - Onboard stereo delay, lush reverb, and harmonic drive.
  - Musical scale quantizer (Major, Minor, Pentatonic, Dorian, Blues, Chromatic).
- **Desktop Keyboard Mode:** Play notes with your computer keyboard with octave shift controls.
- **Zero Installation:** Runs 100% in your browser using the modern Web Audio API and W3C WebHID API.

---

## 🎮 Controller Mapping Guide

| Input | Action |
| :--- | :--- |
| **Tilt / Gyro** | Pitch gliding and vibrato (Motion Mode) |
| **R2 Trigger** | Dynamic note trigger & continuous volume swell |
| **Left Stick (X)** | Scale step selection (Left = lower notes, Right = higher notes) |
| **Left Stick (Y)** | Micro-pitch bend (±2 semitones) |
| **Right Stick (X)** | Filter Cutoff sweep |
| **Right Stick (Y)** | Volume / Dynamics swell |
| **Touchpad Drag** | 2D Filter modulation (X: Cutoff, Y: Resonance) |
| **Touchpad Click** | Quick Mute / Unmute toggle |
| **Cross (✕)** | Instant note trigger / gate |
| **Square (□)** | Toggle Quantize / Free Pitch glide |
| **Triangle (△)** | Cycle Musical Scales (Major, Minor, Blues, etc.) |
| **D-Pad Up / Down** | Shift Octaves (with haptic feedback) |

---

## 🎮 DualSense Controller Setup

1. **Connect your PS5 DualSense controller:**
   - **USB Cable (Recommended):** Connect directly with a USB-C cable for lowest latency and full WebHID access.
   - **Bluetooth:** Hold the `Create/Share` button and the `PS` button simultaneously until the lightbar double-blinks, then pair it in your operating system's Bluetooth settings.
2. In the app, click **"Connect Controller"**.
3. Select **"Wireless Controller"** from the browser's device picker.
4. Move, tilt, and play!

---
