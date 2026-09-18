# The Monument of Eternal Love — Cinematic 3D Taj Mahal Experience

An interactive 3D WebGL experience built with **Three.js, GSAP ScrollTrigger, HTML5, and Vanilla CSS**.

## ✨ Features

- **Iconic Architectural Fidelity**:
  - Procedural Makrana white marble mausoleum with authentic octagonal footprint (*hasht bihisht*).
  - Sweeping bulbous central onion dome with lotus collar and golden *kalash* finial.
  - Four surrounding columned domed pavilions (*chattris*).
  - Four multi-tiered corner minarets with balconies.
  - Long reflecting pool (*charbagh* water canal) with animated specular ripples.
  - Cypress tree avenues and illuminated sandstone walkway lamps.
- **Continuous Cinematic Camera Flight**:
  - **Scroll 0% - 25%**: Wide twilight vista across the reflecting pool.
  - **Scroll 25% - 50%**: Gliding low over the water surface toward the grand marble plinth.
  - **Scroll 50% - 70%**: Ascending and passing through the grand *pishtaq* archway under a swinging brass lantern.
  - **Scroll 70% - 85%**: Seamless transition into the octagonal inner sanctuary with a vaulted starburst dome ceiling and moonlit jali beams.
  - **Scroll 85% - 100%**: Intimate sweep framing the couple holding hands under the lantern, revealing the romantic message.
- **Zero External Model Bottlenecks**:
  - All 3D geometry and marble/pietra dura/star textures are procedurally generated in WebGL, guaranteeing instant loading and no broken asset URLs.
- **Atmospheric Lighting & Web Audio Drone**:
  - Twilight sky dome, warm sun highlights, swinging lantern point light, moonbeams, and floating firefly particles.
  - Built-in meditative ambient synthesizer using the Web Audio API with peaceful harmonic chords and singing bowl chimes.
- **Free Look / Orbit Mode**:
  - At the end of the journey, users can click "Explore 3D Interior" to freely pan, tilt, and zoom around the sanctuary and couple.

## 🚀 How to Open

Simply open `index.html` in any modern web browser (Google Chrome, Microsoft Edge, Mozilla Firefox, or Safari), or serve it using any local static file server:

```powershell
npx -y serve .
```
or
```powershell
python -m http.server 8000
```
