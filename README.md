# 🖤 Night Drive — a BMW M4 Tribute in 3D

**Live experience → [hprince01.github.io/projects/night-drive](https://hprince01.github.io/projects/night-drive/)**

A cinematic, scroll-driven web experience that mixes **real-time 3D**, **parallax photography** and **POV footage of my own black BMW**. Inspired by modern automotive launch sites.

## The story (7 scenes)
1. **Night Drive** — angel-eye headlights flicker on in a dark garage
2. **This one’s mine** — a drone shot of my BMW tilts from a 3D angle to flat, with hotspot labels
3. **Hands on. Eyes up.** — my POV driving clip plays in a floating 3D phone over a deep-parallax background
4. **Born in the dark** — push-in to the headlights + a laser-light card that tilts with the mouse
5. **Real-time 3D** — the camera orbits a WebGL car through 4 views with bloom lighting and a live paint picker
6. **Pure performance** — animated stat counters
7. **Keep driving** — finale

## Built with
- **Three.js** (WebGL, physically based clear-coat paint, Unreal Bloom post-processing, GLTF loader)
- **GSAP + ScrollTrigger** for scroll-scrubbed animation, **Lenis** for smooth scrolling
- CSS 3D transforms for parallax and tilt, IntersectionObserver for video playback
- Responsive layout + reduced-motion support

> **Realistic model:** the page loads `assets/m4.glb` if present (e.g. *BMW M4 CSL 2023* by Black Snow, CC BY 4.0 on Sketchfab); otherwise it renders a car modelled in code.

## Credits
- Photos of my own BMW and POV video: **Prince Hirwa**
- Night photos via [Unsplash](https://unsplash.com): Dmitry Timofeew, Volodymyr Proskurovskyi, Xuan’s gallery, Amir Hosseini, Mathew Antony

*Unofficial fan project. Not affiliated with, endorsed by or connected to BMW AG. BMW and M4 are trademarks of their owner.*

---
Designed & coded by **Prince Hirwa Rutagengwa · [Kai Labs](https://hprince01.github.io/)** — Kigali, Rwanda.
