# Beaconix — Poke-issue-dex №97

*The Fault Pokémon*

![Beaconix](beaconix.png)

**Type:** bug

**Rank:** medium

**Species:** Fault Pokémon  
**Height:** 1.4 m   **Weight:** 26.9 kg

> Beaconix is the Beacon Pokémon: it is meant to blaze amber the instant one of its issuemon siblings pauses to wait on a trainer, flashing a "Needs you!" flare so no creature is ever left calling into an empty map. But #97 finds Beaconix's beacon broken — the needs-attention signal reaches the Region Safari feed but never lights, because a paused-awaiting-input session never sets the flag and the live SSE view refuses to repaint on a needsAttention-only flip until the whole map reloads. Beaconix hunts down that dark link in the data layer and rewires it so the glow, the bubble, and the front-of-lane sort spring to life the moment a trainer is truly needed, then fade the instant the input arrives.
