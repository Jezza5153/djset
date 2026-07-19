# PEAK — Official Site

Scroll-driven site for **PEAK** — Dutch-born, Barcelona-based high-energy drum & bass DJ, co-founder of [DnBabes](https://www.instagram.com/dnbabes_bcn/) (@dnbabes_bcn).

**Concept: "Rotation."** A photoreal jog wheel is the site's through-line — it turns as you scroll, you can grab and scratch it, and it becomes the player when her mix comes in. A living club-light system shifts hue per section and breathes at 174 BPM.

## Run it

```bash
python3 -m http.server 8846
# → http://127.0.0.1:8846/
```

Single self-contained page (`index.html`) — no build step, no dependencies. External requests happen only when a visitor opts in (SoundCloud embed, YouTube embed).

## What's inside

- **The drop-in** — ~1.2s entrance: platter spins up, BPM rolls 000→174, one strobe hit, lights bloom. Skippable, once per session, reduced-motion safe.
- **Rotation** — jog wheel scrubbed by scroll; grab it to scratch (with inertia).
- **Sound on / hero Play** — loads her real SoundCloud mix (track 2158245366); a fixed now-playing chip with STOP is reachable at every scroll depth.
- **Real content only** — verified facts, timeline, and credits per [CONTENT.md](CONTENT.md) (sources included). Real press photo, real video frames, official Liquicity lineup banner.
- Mobile-first pass, ≤600KB page weight, `prefers-reduced-motion` fallback throughout.

## Before public launch

- Confirm with PEAK: press-photo usage rights, "founder vs co-founder" wording.
- Swap `bookings@` placeholder contact if needed; add her preferred booking email.
- Optional: her IG reels as muted hero/finale loops (she can export her own).

Built with Claude Code.
