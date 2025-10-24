<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Web%20Audio%20API-0084D6?style=for-the-badge" alt="Web Audio API">
</p>

# Sleep Sounds Studio

An advanced, generative noise engine for deep rest, creative focus, and mindful breaks. No ads, no interruptions—just pure, customizable soundscapes running entirely in your browser.

<p align="center">
  <img src="https://github.com/user-attachments/assets/44933d7b-dcd1-4fff-abda-92b87d58843f" alt="Sleep Sounds Studio UI" width="600">
</p>

---

## The Story Behind This Project

This project started on a vacation with a simple problem: I needed a white noise generator to help me sleep, but I didn't want to use YouTube. The last thing you want when you're drifting off is a loud ad waking you up. I figured, "How hard can it be to generate some noise in a browser?"

So, I built a quick and simple white noise machine in a single HTML file. It worked perfectly for its intended purpose.

But then I got curious. The Web Audio API is incredibly powerful, and I started wondering what else I could create with it. This led to experimenting with different "colors" of noise, spatial audio effects, and preset configurations. I added stereo panning, autopan drift, session timers with gentle fade-outs, and tone sculpting to shape the sound exactly how you like it.

What began as a practical tool to block out noise evolved into this—a full-featured generative soundscape studio. It's a testament to how a simple need can blossom into something truly useful.

---

## Features

### Sound Design
- **Three Noise Palettes:** Choose from three scientifically-tuned noise colors to find the perfect foundation for your soundscape.
  - **White Noise:** A sharp, hissing sound containing all frequencies at equal intensity. Excellent for masking high-pitched noises and maintaining alertness.
  - **Pink Noise:** A balanced, waterfall-like sound with reduced high frequencies. Many find it less fatiguing than white noise and ideal for sleep.
  - **Brown Noise:** A deep, rumbling sound emphasizing low frequencies. Perfect for a calming, immersive hum that promotes relaxation.

- **Tone Sculpting:** A precision low-pass filter lets you shape the character of your noise in real-time. Roll off harsh highs for a softer, muffled texture or push toward brightness for crisp brilliance.

- **Volume Control:** Carefully calibrated to encourage longer, more comfortable listening sessions at modest levels.

### Motion & Space
- **Stereo Positioning:** Pan the sound left or right across your stereo field for directional immersion.
- **Gentle Autopan Drift:** Enable a slow, sine-wave stereo sweep that creates an immersive sensation of movement without distraction. Customizable intensity per preset.

### Session Management
- **Auto Fade-Out Timer:** Set a duration (5 to 120 minutes) and the generator will gently fade the sound before stopping playback. Perfect for drifting off naturally without abrupt endings.
- **Status Updates:** Real-time feedback on your playback state and session configuration.

### Quick Presets
Instantly load pre-configured sessions tuned for different activities:
- **Deep Sleep:** Warm brown noise, soft tone, 45-minute fade, slow autopan. Designed for restful sleep.
- **Laser Focus:** Bright pink noise with subtle stereo movement. Perfect for creative work and deep concentration.
- **Rainy Night:** Muted white noise with gentle sway and a 30-minute timer. Evokes a cozy, stormy atmosphere.
- **Mindful Breath:** Balanced pink noise, centered pan, and a short 10-minute fade. Ideal for meditation and breathing exercises.

### Technical
- **Ad-Free & Uninterrupted:** No ads, no tracking, no interruptions. Ever.
- **Single File, Zero Installation:** Everything runs locally in your browser using the Web Audio API. No servers, no setup, no dependencies.
- **Responsive Design:** Works seamlessly on desktop, tablet, and mobile devices.
- **All Local Processing:** Your session data and preferences stay on your device. Complete privacy.

---

## How to Use

Since this is a self-contained HTML file, there's no installation required.

1. Download the `index.html` file from the repository.
2. Open the file in any modern web browser (Chrome, Firefox, Safari, Edge).
3. Click **"Start Session"** to begin.

That's it! The interface will guide you through customizing your soundscape.

---

## Controls & Layout

### Playback Panel
- **Play/Stop Button:** Start or stop your soundscape session.
- **Status Display:** Real-time feedback on playback state, timer status, and any active effects.
- **Sound Visualizer:** A subtle animated wave that indicates when sound is actively playing.

### Noise Palette
- **Noise Type Buttons:** Switch between White, Pink, or Brown noise instantly.
- **Volume Slider:** Adjust overall loudness (0–100%).
- **Tone Sculpting Slider:** Shape the frequency response from warm and muffled (left) to bright and crisp (right).

### Motion & Space
- **Stereo Position Slider:** Pan the sound across the stereo field (−100 to +100).
- **Autopan Toggle:** Enable a gentle, slow stereo sweep for immersive depth.

### Session Timer
- **Auto Fade-Out Slider:** Set a duration from 0 to 120 minutes in 5-minute increments.
- **Fade Behavior:** When time expires, the sound gradually fades over 12 seconds before stopping.

### Quick Presets
- **Preset Buttons:** Click any preset to instantly apply a complete, pre-tuned configuration.

---

## Tech Stack

- **HTML5:** Semantic markup and accessibility standards.
- **CSS3:** Modern layout with CSS Grid, flexbox, gradients, and glassmorphism effects.
- **JavaScript (ES6+):** Clean, modular class-based architecture for the audio engine.
- **Web Audio API:** Core technology for all sound generation, filtering, panning, and effects.

---

## Browser Compatibility

Sleep Sounds Studio works on all modern browsers that support the Web Audio API:
- Chrome/Chromium (v25+)
- Firefox (v25+)
- Safari (v6+)
- Edge (v79+)

For the best experience, use the latest version of your browser.

---

## License & Attribution

This project is open source and available for personal and commercial use. All rights reserved © 2025.

Built with care by **Matthew Wesney**.

---

## Contributing & Feedback

Have ideas for improvements? Found a bug? Feel free to open an issue or submit a pull request. Feedback is always welcome and helps make Sleep Sounds Studio better for everyone.

---

## Disclaimer

Sleep Sounds Studio is designed as a relaxation and focus aid. It is not a medical device and should not be used as a substitute for professional sleep therapy or medical treatment. If you experience persistent sleep issues, please consult a healthcare professional.
