BREACH.exe — Gameplay 2.0

Open index.html in a modern browser. Works offline and on GitHub Pages.

Mechanics:
- Rotate channels by clicking/tapping. Connect ENTRY to SERVER.
- Mission 3 onward: ICE FIREWALL blocks routing; rotating nodes increases TRACE. Failed injections increase TRACE 18%. 100% means detection.
- Mission 4 onward: a SPLITTER node branches to a fixed RELAY (marked R). Both RELAY and SERVER must receive packets.
- Mission 5 onward: packets can travel up to 8 connected nodes before expiring; BOOSTER nodes (lightning symbols) replenish the packet.
- Reset costs +7% TRACE; a hint costs +6%. Early missions omit TRACE.
- Progress and sound settings stored in localStorage.

Assets: assets/tiles, assets/objects, assets/branding, assets/screens and assets/ui.

No build tools or external dependencies.

GAMEPLAY 2.1 — PROGRESSIVE DIFFICULTY
Mission 01: basic routing, no TRACE, no firewalls, no splitter or booster.
Mission 02: routing practice, no advanced mechanics.
Mission 03: larger routing practice, no advanced mechanics.
Mission 04: ICE firewalls and TRACE detection are introduced.
Mission 05: splitter + a required relay branch are introduced.
Mission 06: boosters and 8-hop packet energy limit are introduced.
Missions 07-08: combined mechanics and tougher networks.
Progress and records remain in localStorage under breach-save-v1.


Visual & Audio Polish update:
- animated signal packet with brighter active route feedback
- success/failure screen and board FX
- richer UI transitions and shimmer/glitch polish
- ambient synth bed and improved SFX for rotate, inject, relay, booster, success, failure, TRACE alert
