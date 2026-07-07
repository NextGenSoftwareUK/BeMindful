# Be Mindful

**Daily Mindfulness & Meditation · OASIS Omniverse**

Be Mindful is a daily mindfulness, meditation, breathwork and yoga companion — one of the applications within the [OASIS Omniverse](https://oasisomniverse.one) ecosystem. Every practice session earns OASIS karma, which carries across every connected app in the ecosystem.

## What is Be Mindful?

- **Daily mindfulness prompts** — short, actionable practices for morning, afternoon and evening
- **Guided meditation sessions** — timed sessions with breathing cues and ambient audio
- **Breathwork exercises** — box breathing, 4-7-8, Wim Hof-style techniques
- **Yoga flows** — beginner to advanced sequences with pose guides
- **Wellbeing tracking** — mood, energy and sleep journalling with visual history
- **Karma integration** — every completed session awards OASIS karma via the Web4 API

## Tech Stack

| Layer | Detail |
|---|---|
| Front-end | Single-file `index.html` — inline CSS + vanilla JS |
| Fonts | Orbitron, Rajdhani, Share Tech Mono (Google Fonts) |
| OASIS API | `@oasisomniverse/web4-api@2.0.2` via esm.sh |
| Hosting | Static — any CDN or static host |

## Running Locally

```bash
npx serve .
# or
python -m http.server 8080
```

---

*Part of the [OASIS Omniverse](https://oasisomniverse.one) · Powered by OASIS Web4*
