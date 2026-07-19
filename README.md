# PEAK — Five Sets

Five concept directions for a scroll-driven site for **PEAK** — high energy drum & bass, 174 BPM, Barcelona.

Same artist, same story, five signature mechanics:

| # | Set | Signature |
|---|-----|-----------|
| 01 | [Enter the Set](v1.html) | The page is arranged like a DnB track — BPM builds 000→174, then the drop |
| 02 | [Velocity](v2.html) | Scroll speed distorts the typography — stop and it settles into the groove |
| 03 | [Waveform](v3.html) | One giant waveform river; scrolling scrubs the playhead through cue points |
| 04 | [Afterhours](v4.html) | Cinematic dark-room: full-bleed stills, sweeping light, strobe cuts |
| 05 | [Rotation](v5.html) | The jog wheel as through-line — scrubbed by scroll like vinyl |

**[index.html](index.html)** is the chooser hub.

Every set is a single self-contained HTML file — no frameworks, no build step, no external requests. System fonts, canvas waveforms, one shared 174 BPM clock, `prefers-reduced-motion` fallbacks, mobile-aware.

## Run

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8844
# → http://127.0.0.1:8844
```

## Notes

- Imagery: AI-generated concept stills (Pioneer-style gear) — swap for live photography.
- Booking form is a demo (nothing is sent).
- Built at 174 BPM.
