# Lunar Descent II: Fuel Run — Release Notes

## v1.1 "Mission Update" — September 16, 2026

The biggest update since launch. Landing is no longer the whole game: each sector now
has jobs to do, things to avoid, and a reason to come back and beat your score.

### New gameplay
- **Sectors.** Clear three different scoring pads to advance to the next sector. Each
  sector generates a fresh landscape, and pads no longer end the round on their own —
  you lift off and keep flying.
- **Cargo runs.** A crate sits on one scoring pad. Land there to load it, then deliver it
  to the pad marked **DEST** for a +400 bonus. Cargo makes the lander noticeably heavier.
- **Rescue missions.** A stranded astronaut waves **SOS** from a rough ledge. Set down
  beside them to bring them aboard, then dock at the orbital station (or a fuel depot if
  there is no station this sector) for +500.
- **Timed fuel depots.** A depot's pump light starts blinking when you first dock, and it
  goes **OFFLINE** about 20 seconds later. Plan your refuels; the station never closes.
- **Hazards.** Drifting rock debris appears from sector 2 and grows in number each sector.
  From sector 4, meteor showers streak diagonally across the sky (a warning tone sounds
  when one is inbound).
- **Difficulty ramp.** Gravity rises about 7% per sector (up to 1.6x), scoring pads shrink
  from sector 3, and wind gets stronger.
- **Wind.** Many sectors have a lateral drift, shown in the HUD as `WIND ◀◀` / `▶▶▶` or
  `CALM`, with the direction also announced at the start of the sector.

### Feedback and scoring
- **High score table.** Top five scores with initials, saved in your browser. Shown on the
  title screen and at game over.
- **Landing readout.** Every touchdown shows the vertical and horizontal speed you actually
  hit (`V 36  H 3`), so you can learn to feather it.
- **Mission log** at game over: sectors reached, landings and perfects, softest touchdown,
  fuel taken on, distance flown, cargo delivered, crew rescued, landers lost.
- **HUD additions:** sector and pad progress, wind, and a LOAD line showing CARGO / CREW.

### Presentation
- Screen shake and a white flash on crashes.
- Scanline and vignette overlay for a vector-monitor look.
- New sound cues for pickups, deliveries, rescues, and incoming meteors.
- Landscape prompt on phones held in portrait.

### Fixes and tuning
- Fixed a landing-leg bug that made docking on the station crash the lander.
- Fixed a station truss line poking out of the right side of the hull.
- Landing envelope loosened: vertical speed under 65, horizontal under 24, roughly upright.

---

## v1.0 — September 8–13, 2026

- Vector-style lander in the spirit of the 1979 arcade original.
- **Fuel depots** on the surface and an **orbital space station** that refill the tank,
  so a run can go on as long as you can fly it.
- Tall mountains and valleys with the best pads on the valley floors.
- A wide side-scrolling world (6,400 units) with a locator marker for the station.
- Synthesized engine, thruster, touchdown, crash, refuel, and low-fuel sounds.
- Pause (P / Esc, or ‖ on phones), touch controls, and a mobile-friendly layout.
- Deployed as a single HTML file on GitHub Pages.
