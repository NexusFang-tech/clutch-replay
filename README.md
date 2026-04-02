# CLUTCH::REPLAY — Fortnite Match Storyteller

Animated match replay tool for Fortnite. Input key moments from your game and watch them play back as a cinematic timeline with a kill feed, placement tracker, event flashes, and auto-generated hype commentary.

## Live Demo

**[nexusfang-tech.github.io/clutch-replay](https://nexusfang-tech.github.io/clutch-replay)**

## Features

- **Animated replay canvas** — dark synthwave-style match viewer with grid background, HUD overlay, and timeline bar
- **6 event types** — Kill, Knocked, Revive, Rotate, Storm, Clutch — each color-coded on the timeline
- **Kill feed** — recent events fade in/out in the top-right corner, like the in-game feed
- **Event flash** — key moments display center-screen with the event type label and description
- **Placement tracker** — alive count ticks down during the replay, snaps to final placement at the end
- **Auto-commentary** — each event triggers randomized hype commentary text below the canvas
- **Scrub timeline** — drag the progress bar to jump to any point in the match
- **3x speed** — replays run at 3x real time so a 22-minute match plays in ~7 minutes
- **Pre-loaded demo** — ships with a sample VR match (8 kills, Trios, Ch7 S2)
- **Add/remove moments** — dynamically add or delete events with timestamps
- **Copy match report** — generates a text summary of all moments for sharing in Discord
- **Pause/resume/replay** controls

## Event Types

| Type | Color | Description |
|------|-------|-------------|
| Kill | Pink | Elimination — the bread and butter |
| Knocked | Orange | Teammate or self knocked |
| Revive | Cyan | Clutch revive |
| Rotate | Purple | Storm rotation or repositioning |
| Storm | Yellow | Storm-related moment (surge, circle close) |
| Clutch | Green | The highlight play — final fight, game-winning moment |

## Match Report Format

The copy button generates shareable text:
```
CLUTCH::REPLAY
NexusFang | Trios | #1 | 8 elims | 22:15

[2:30] ELIMINATION: Eliminated Player_247 with Chaos Reloader
[5:10] ELIMINATION: Eliminated TTV_Sweat99 with Vector 7 DMR headshot
[14:20] ELIMINATION: Triple kill on squad pushing from north
[21:30] CLUTCH MOMENT: 1v1 final circle — Chaos Reloader 180 flick for the VR
```

## Tech Stack

Vanilla JavaScript · HTML5 Canvas · Zero Dependencies · GitHub Pages

## Author

**Matt Keith** · [nexusfang-tech.github.io](https://nexusfang-tech.github.io)
