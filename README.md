# Portfolio — Nemani Anirudh

A single-page personal portfolio site with a cyberpunk / terminal-inspired design —
custom cursor, animated circuit-board background canvas, scroll-reveal sections, and
a client-side validated contact form.

## Sections

- **Hero** — name, title, rotating tagline, animated avatar ring with floating skill chips
- **About** — summary + quick stats (CGPA, projects, FPGA speedup, patents)
- **Education** — degree history with scores/years
- **Technical Skills** — categorized tag grid (microcontrollers, protocols, languages, tools, FPGA, sensors, etc.)
- **Projects** — FPGA soil nutrient analyzer, IoT motor protection, assistive pen/pad, species recognition
- **Experience** — internships, workshops, club roles
- **Certifications** — MATLAB/Simulink Onramp, Python Basics
- **Contact** — email/LinkedIn/phone links + a validated contact form

## Tech

Plain HTML/CSS/JS — no build step, no framework, no dependencies. Fonts loaded from
Google Fonts (Share Tech Mono, Rajdhani, Exo 2). All animation (cursor, canvas
particles, waveform, scroll-reveal) is hand-rolled vanilla JS.

## Running locally

Just open `index.html` in a browser, or serve it:

```bash
npx serve .
```

## Notes / TODO

- The contact form currently only validates client-side and shows a success message —
  it does **not** actually send anything. Wire it up to a backend or a service like
  Formspree/EmailJS if you want real submissions.
- Content doesn't yet include the Seisou Labs internship, AquaGuard AI project, or
  SkillSwap — update the Projects/Experience sections if you want those reflected.
- Fully responsive down to mobile, but the animated avatar/chips are hidden under 920px.

## Deploying

Static file, so it works as-is on GitHub Pages, Netlify, or Vercel — no build config needed.
