# DualWave 🌊🎮

An expressive motion synthesizer and continuous lead instrument playable with a **PlayStation 5 DualSense controller** (via WebHID or Gamepad API), **Touch Ribbon**, and **Computer Keyboard**.

---

## 🌟 Live Demo

👉 **[Play now.](https://grandsummoner.github.io/dualwave/Dualwave-synthesizer.html)**

> **Browser Requirement for DualSense Controller:** Use Google Chrome, Microsoft Edge, or any Chromium-based desktop browser for full **WebHID** gyro motion and touch-pad support over HTTPS.

---

## 🎹 Features

- **PS5 DualSense Motion & Touch Control:**
  - **DualSense Touchpad:** Plays the ribbon directly (X: Pitch along scale, Y: Volume & Dynamics).
  - **Analog Sticks (Effects Knobs):** Left stick sculpts stereo delay (Time & Mix); right stick sweeps filter cutoff and reverb mix.
  - **Gyro & Accelerometer:** Pitch and tilt the controller to glide pitch and control vibrato like a digital Theremin.
  - **Analog Triggers (L2/R2):** Smooth volume and dynamics control with adaptive trigger resistance.
  - **Haptic & Lightbar Feedback:** Real-time LED colors match current pitch and musical root.
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
| **Touchpad Drag** | **Play Ribbon** (X: Pitch along scale, Y: Volume / Dynamics) |
| **Touchpad Click** | Quick Mute / Unmute toggle |
| **Left Stick (X)** | Delay Time (0.05s to 0.8s) |
| **Left Stick (Y)** | Delay Mix (Dry/Wet) |
| **Right Stick (X)** | Filter Cutoff sweep (100Hz to 12kHz) |
| **Right Stick (Y)** | Reverb Mix (Dry/Wet) |
| **R2 Trigger** | Dynamic note trigger & continuous volume swell |
| **Tilt / Gyro** | Pitch gliding and vibrato (Motion Mode) |
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
4. Touch the pad, move the sticks, and play!

---

# Start local development server
npm run dev
