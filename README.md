An embeddable, clickable prototype of **SoulSync** — an AI-powered "My Journey" companion concept designed for the **Psychic Source** customer experience.

SoulSync helps customers track their personal journey *between* readings: life events, reflections, saved questions, milestones, and reading insights, woven into one interactive timeline. AI surfaces recurring themes and growth over time. It is a reflection tool — **not** an AI psychic; human advisors remain at the heart of every reading.

## Live demo

▶️ **[View the prototype](https://soulsync-my-journey.vercel.app/)**

> Replace the link above with your Vercel URL once deployed.

Tap through all ten screens, the bottom navigation, and the **+** Reflect button. Saving a reflection or life event triggers the live AI insight and success states.

## What's in here

- `index.html` — the self-contained prototype (HTML, CSS, and JavaScript in one file). It auto-scales to fit whatever width it's placed in. The only external dependency is Google Fonts (Cormorant Garamond + Outfit).

## Embedding on another site

Host this repo on Vercel (or any static host), then drop in this snippet — the wrapper keeps the phone's proportions responsive on any screen:

```html
<div style="max-width: 420px; margin: 0 auto;">
  <div style="position: relative; width: 100%; aspect-ratio: 390 / 818;">
    <iframe src="https://YOUR-PROJECT.vercel.app" title="SoulSync prototype" loading="lazy"
      style="position: absolute; inset: 0; width: 100%; height: 100%; border: 0; border-radius: 24px;" allowfullscreen></iframe>
  </div>
</div>
```

## Screens

Welcome · Home · My Journey (timeline) · Add Life Event · Daily Reflection · Question Keeper · AI Patterns · Monthly Reflection · Reading Recall · Profile & Settings.

## Sample journey

The demo follows **Elena**, across six months of career change, reconnection, and growing self-trust — from "feeling stuck" in January to accepting a new role in June.

---

*Concept prototype for review. Not affiliated branding-final; colors and copy are illustrative.*
