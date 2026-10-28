# MirrorMind — Interactive Showcase Website (v2)

Ideation-stage showcase for MirrorMind: an AI + psychology platform for students at life turning points.

**In my own words:** I wanted a place where I could figure out who I was before I had to decide what to do next.

## What changed in v2

- **Look:** plain white background (#FFFFFF), text #1D1D1F, secondary text #86868B, grey cards #F5F5F7, and Klein blue #0071E3 as the only accent colour. Serif display type (New York / Georgia, with Songti for Chinese) paired with clean sans body type, 16px card radius, no shadows, no dark orange hero.
- **Voice:** the whole narrative is written in the first person, in my voice, explaining my own concept. There is no third-person “founder thesis” framing.
- **Language:** bilingual throughout. Use the **English / 中文** switch at the top for the main narrative. Stat captions, demo labels, the theory table, and the footer are presented in both languages.
- **Human-language filter:** the copy was checked against common AI-writing tells and rewritten in flowing, conversational sentences, with concrete examples and personal reasoning, instead of short punchy slogans, dramatic contrasts, or abstract buzzwords. No em dashes, no “seamless”, “empower”, “delve”, “moreover”, or similar stock AI phrasing in the narrative copy.

## What is in this folder

- `index.html` — the complete interactive site. No build step, no external dependencies.
- `assets/` — the five founder-supplied images:
  - `threshold.jpg` — existential threshold / future (hero)
  - `city-of-paths.jpg` — unlimited paths
  - `information-wave.jpg` — information overload
  - `fragmented-self.jpg` — fragmented identity / identity overload
  - `clear-screen.jpg` — one calm screen, depth on demand

## Sections

1. Problem — identity without an anchor, in my words
2. Evidence — U-curve collapse, Gen Z distress figures, digital-tool preference
3. Jam experiment — interactive 6 vs 24 choice demo (Iyengar & Lepper, 2000)
4. Product — Know → Explore → Act, 30 seconds a day, in my words
5. Interactive demo — identity-card generator, chat-triggered hidden tools, personal agent vs generic chatbot
6. Business — Xiaohongshu-first validation, prototype + funnel data, free daily layer / paid depth / B2B2C
7. Theory → product map
8. Sources & honesty note (APA-style, selected)

## Interactive demos

All demos run in the browser only. No data is sent anywhere and nothing is stored:

- **Jam experiment:** switch between 6 and 24 options to see the conversion bar change.
- **Identity card:** choose a value, a pressure, and a dilemma to generate a shareable card in the first person, then copy its text.
- **Chat tools:** type “I’m stuck”, “simulate”, or “milestone” to bring out a hidden tool, mirroring MirrorMind’s progressive-disclosure design.

## Upload to GitHub

1. Create a new GitHub repository (public if you want GitHub Pages).
2. Upload the contents of this folder — `index.html`, `README.md`, and the whole `assets/` folder — to the repository root. Keep the folder structure exactly as it is, so `index.html` can find `assets/*.jpg`.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. GitHub will publish the site at `https://<your-username>.github.io/<your-repo>/`.

To preview locally before uploading, open `index.html` in any browser, or run a local server from this folder, for example:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000/

## Important notes

- This is an ideation-stage showcase, not a medical product. MirrorMind is not therapy, does not diagnose, and does not replace a counsellor.
- No pricing, market-size, or conversion figures are invented on the site. Those are validation outputs.
- Survey figures are presented as cited in the MirrorMind business plan. Verify full reports before a formal pitch or publication. The Spotify Wrapped viral-sharing figure is deliberately not used as a headline number because its supplied source needs independent checking.
