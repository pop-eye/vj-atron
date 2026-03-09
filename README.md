# VJ-ATRON — Browser VJ Station

A fully browser-based VJing station for teaching the fundamentals of live video performance. No installation required — just open `index.html` in Chrome or Edge.

---

## Getting Started

1. Open `index.html` in **Google Chrome** or **Microsoft Edge** (recommended for best performance)
2. Click **LAUNCH VJ-ATRON** on the splash screen
3. Click **LOAD FOLDER** in the library panel and navigate to your **OneDrive Videos** folder
4. Your clips will appear as thumbnails — hover to load them to **Deck A** or **Deck B**

---

## VJing Fundamentals Covered

### 1. Dual Deck System
Like a DJ's twin turntables, VJ-ATRON has **Deck A** (cyan) and **Deck B** (pink). Each deck plays an independent video clip, giving you two visual sources to mix between.

### 2. The Crossfader
The central horizontal slider mixes between the two decks:
- **Far left** → only Deck A is visible
- **Far right** → only Deck B is visible
- **Centre** → both decks are blended together

### 3. Blend Modes
When both decks are visible, **blend modes** control how their pixels are combined:
| Mode | Effect |
|------|--------|
| Normal | Standard layering by opacity |
| Screen | Both decks brighten each other (good for dark footage) |
| Multiply | Both decks darken each other |
| Overlay | High contrast mix — darks multiply, lights screen |
| Add (Lighter) | Pixel values are added — very bright and energetic |
| Difference | Subtracts pixels — creates trippy inversion effects |

### 4. BPM & Beat Sync
- Tap the **TAP** button in time with music to set your BPM
- The orange beat indicator flashes in time
- Use this to trigger transitions, effects, and cuts on the beat

### 5. Per-Deck Effects
Each deck has its own FX chain in the right panel:
- **BRI** — Brightness
- **CON** — Contrast
- **SAT** — Saturation (colour intensity)
- **HUE** — Hue rotation (shifts all colours)
- **BLR** — Blur
- **INV** — Invert colours

### 6. Master FX & Colour Grading
Apply a unified look to the output:
- **Colour grades**: Warm, Cool, B&W, Sepia, Neon, Night
- **ZOOM / ROT** — scale and rotate the entire output
- **Mirror H/V** — flip the output horizontally or vertically

### 7. Playback Controls
- **Speed** — slow motion (0.1×) to fast forward (3×)
- **Loop** — seamless clip looping
- **Cue** — set a cue point and jump back to it instantly (key performance technique)
- **Progress bar** — seek any clip by clicking the bar

### 8. Strobe Effect
The strobe rapidly flashes the output on/off at a set Hz frequency. Use sparingly and responsibly.

---

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `SPACE` | Play / Pause Deck A |
| `ENTER` | Play / Pause Deck B |
| `← / →` | Move crossfader left/right |
| `Z / X` | Deck A speed − / + |
| `N / M` | Deck B speed − / + |
| `T` | Tap BPM |
| `S` | Toggle Strobe |
| `L` | Toggle Loop A |
| `K` | Toggle Loop B |
| `Q / W` | Set / Go to Cue A |
| `O / P` | Set / Go to Cue B |

---

## About VJing

**VJing** (Video Jockeying) is the live manipulation and mixing of video visuals in real time, typically synchronized to music at events, concerts, clubs, and art installations.

Key skills in VJing:
- **Beat matching** — syncing visual cuts and transitions to musical tempo
- **Visual layering** — combining multiple video sources with blend modes
- **Reactive FX** — applying effects that respond to the energy of the music
- **Clip management** — curating a library of footage and knowing when to use each clip
- **Live improvisation** — making creative decisions in real time

---

## Tips for Students

1. **Start simple** — load two clips and practice moving the crossfader smoothly
2. **Use Loop** — looping clips gives you infinite time to focus on the mix
3. **Set cue points** — mark the best moment in a clip and trigger it precisely
4. **Match the energy** — use bright/fast clips for energetic music, slow/abstract for ambient
5. **Blend modes are powerful** — Screen and Add work great with dark footage and particle effects
6. **Colour grade unifies the mix** — apply a grade to make two different clips feel like one visual world
7. **Less is more** — beginners often over-effect; restraint makes a stronger performance

---

## Technical Notes

- Works entirely in the browser — no server, no plugins
- Uses HTML5 Canvas API for real-time compositing
- Video is processed using CSS filters via the Canvas 2D context
- File access uses the browser's native `<input type="file" webkitdirectory>` API
- Works best in **Chrome 90+** or **Edge 90+**
- For best performance close other browser tabs when performing live
