# Drini Bird 🚗💨

A Flappy-Bird-style browser game – but instead of a bird, you fly a **black BMW M850i** through construction barriers over a night city skyline.

**▶ Play now (works on iPhone):** https://dalipivaldrin.github.io/drini-bird/

## How to Play
- **Tap** the screen (or press Space / ↑) to give the car a boost
- Fly through the gaps between the barriers
- Every barrier you pass = 1 point
- The game gets faster and the gaps get tighter as your score goes up
- Your best score is saved on your device

**Tip for iPhone:** open the link in Safari → Share → *Add to Home Screen* to play it fullscreen like an app.

## How I Built It
- **Single file:** everything lives in `index.html` – HTML5 Canvas + plain JavaScript, no libraries, no image or sound files
- **Mobile first:** touch input, no zoom/scroll, sharp rendering on Retina screens (`devicePixelRatio`), scales to any screen size
- **Physics:** simple gravity + upward impulse per tap, car tilts based on vertical speed
- **Graphics:** the car (with spinning rims, exhaust flames and blue brake calipers), the barriers and the parallax city skyline are all drawn in code
- **Sound:** V8-style engine sound, score and crash sounds generated live with the Web Audio API
- **Difficulty:** speed increases and gaps shrink with every point

## Run Locally
Download the repo and open `index.html` in your browser.

---

Developed by **Valdrin Dalipi** – with AI assistance (Claude).
