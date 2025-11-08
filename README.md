# planetary_defender

# SWARM DEFENSE v2.1 — Fruit Fly Brain Satellite Control (Demo)

Fruit-fly–inspired satellite swarm that detects, focuses solar power, and deflects inbound asteroids. Single-file demo. No build. Runs locally in any modern browser.

[![Static Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-informational)](#deploy-to-github-pages)
[![License](https://img.shields.io/badge/License-Apache--2.0-blue.svg)](LICENSE)

Runs locally in any modern browser. No build.

## Run
- Double-click `index.html`, or:
  python3 -m http.server 8000  # then visit http://localhost:8000/index.html

## Controls
- Mouse drag: orbit camera
- Wheel: zoom
- SPACE: auto-engage
- A: toggle AI
- T: lock nearest target
- D: deploy 10 more sats
- R: reset

## Notes
- Scale: 1 AU (game) = 150,000 km
- Mirrors: 1,000 m² per sat; ablation → ṁ; thrust = ṁ·v_exh; lateral Δv maximizes miss distance
- Fly-inspired control: CX (heading), AL (sparse sense), MB (valence/dopamine), LAL (action gating)

License: Apache-2.0 (demo). Sovereign/defense modules remain private. michael@pqg.info for licensing.
