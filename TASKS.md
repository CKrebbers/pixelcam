# Pixelcam — taken

## Ronde v7 (23 okt 2026)
- [x] Geluid in video-opnames (microfoon)
- [x] Reageren op muziek (niveau, beat, BPM) gekoppeld aan animaties en glitch
- [x] Fullscreen live-modus (overlaybalk, toetsen, scherm-aan)
- [x] Presets (6 ingebouwd + eigen opslaan/wissen)
- [x] Prestaties: kleur-LUT, 30 fps-cap, automatische LITE-stand
- [x] HUD-tekst scherp op hoge resolutie, los van pixelgrootte
- [x] Versienummer zichtbaar
- [x] Test: nep-camera + nep-microfoon, opname met audiotrack
- [x] Push, Pages-build, artifact

## Gevonden in ronde v7
- Beatdetectie op basgemiddelde faalt door dB-schaal → vervangen door onset-detectie (bas-stijging t.o.v. vorig frame); test: kick 120 BPM → BPM 120
- In de Claude-artifact werken camera en microfoon niet (viewer blokkeert); muziekreactie en geluid alleen via GitHub Pages

## Later
- Gezichtsherkenning voor de HUD
- Varve-watermerk
- Eigen figuren tekenen in de app
- Geluid van gekozen videobestanden meenemen in de opname
