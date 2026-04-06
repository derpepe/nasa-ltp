# NASA Lunar Targeting Package – LTP FINAL

Nachbau der offiziellen **Artemis II Lunar Targeting Package (LTP)** Web-App, die beim Mondvorbeiflug am 6./7. April 2026 eingesetzt wurde.

## Features

- Interaktive Mondkarte (Canvas) mit Orientale Basin, Maaren, Kratern
- 20 Science-Targets mit GMT-Zeitplan (kompletter Flyby 20:45–01:20 GMT)
- Target-Detailpanel: Target Information, Camera Actions, Unaided Eye Actions
- 4 Tabs: Targets · Timeline · Overview · Guide
- 5-stufiger Beobachtungs-Workflow (Feature ID → Geometry → Color & Shadow → Structure & Texture → Geologic Relations → Thoughts)
- Kamera-Zoom-Modi: Unaided Eye / 135 mm / 200 mm / 400 mm
- OneNote-Notizbuch, Labels-Toggle, Cue Card
- Lebende GMT-Uhr

## Datenquellen

- [NASA LTP Guide (PDF)](https://assets.science.nasa.gov/content/dam/science/missions/artemis/ArtemisII_LunarTargetingPlan.pdf)
- [NASA Science – Artemis II Lunar Targeting Plan](https://science.nasa.gov/resource/artemis-ii-lunar-targeting-plan/)
- [NTRS – Artemis II Lunar Observations Support Software](https://ntrs.nasa.gov/citations/20260001932)

## Deploy

Reines Static-Site-Deployment – kein Build-Schritt nötig.

**Netlify:** `netlify.toml` ist enthalten. Publish-Verzeichnis: `.` (Root)
