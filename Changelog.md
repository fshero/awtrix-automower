# Changelog

All notable changes to this project will be documented in this file.

## [1.3] - 2026-10-28

### Added
- Direct Husqvarna Automower Connect Cloud API integration via OAuth2 client credentials.
- 52x16 pixel layout tailored for Ulanzi TC002 with a 20x16 live diorama on the left and real-time telemetry on the right.
- 7 animated diorama states:
  - Mowing: sinusoidal glide across lawn, uncut blades ahead, rotating wheels, cutting disc shimmer, and animated grass clippings.
  - Charging: docked position with animated flowing blue energy particles.
  - Parked / Sleeping: docked position with rising sleep particles and restriction status support (Frost Guard, Daily Limit, Completed).
  - Leaving: departing dock animation.
  - Going Home: returning to dock animation.
  - EPOS / Planning: satellite pulse waves during GPS fix or path computation.
  - Error: flashing warning beacon with exact Husqvarna error code display.
- Dynamic telemetry area:
  - Battery percentage text with color thresholds (green, orange, red).
  - Battery icon with level fill and animated charge cycle.
  - Scrolling status text for activity, restrictions, and next scheduled start time (>HH:MM).
  - Bottom activity / progress bar with traveling photon dot.
- Interactive manual refresh on middle button press.
- Native AWTRIX Web UI configuration fields for API keys, polling interval, colors, and alerts.
