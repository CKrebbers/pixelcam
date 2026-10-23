# Pixelcam
- **Waarom:** live camerafilter dat beeld omzet naar pixelart (palet, dithering, raster).
- **Voor wie:** Clay (Varve), voor content en als AV-bouwsteen.
- **Doel:** één statische pagina (index.html, geen build) die op telefoon via https live werkt.
- **Hosting:** statisch; varve.nl (TransIP) of GitHub Pages. Camera werkt alleen via https.
- **Let op:** in de Claude-artifactviewer is live camera geblokkeerd; daar valt de pagina terug op de fotocamera.

## Functies (v9)
- Live camera, foto/video kiezen, PNG en video (MP4/WebM, met microfoongeluid) bewaren
- Palet, kleurniveaus, dithering, raster; 10 animaties (kat, fiets, vogels, regen, fonkels, hartjes, glitch, hud, drones, data-regen)
- Reageert op beweging (camera) en muziek (microfoon: niveau, beat, BPM)
- Presets (6 ingebouwd + eigen), Willekeurig-knop, fullscreen live-modus, toetsen F/R/W/←/→/1–9
- Bediening: alle opties als dropdowns/schuiven; beeld blijft vast bovenaan (telefoon) of naast de opties (≥900 px); in fullscreen opent ‘Opties’ (toets O) het paneel onder het beeld
- Prestaties: max 30 fps, kleur-LUT, automatische LITE-stand bij traag toestel

## Werkregels
- Verhoog `VERSION` in index.html bij elke release (zichtbaar onderaan de pagina)
- Testen: headless Chromium met `--use-fake-device-for-media-stream` en een kick-WAV als nep-mic
- Artifact-versie = index.html zonder eigen `<html>/<head>/<body>`-skelet
