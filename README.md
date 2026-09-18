# Web Drum Machine V3

Versione statica pronta per GitHub Pages. Nessun npm, backend o libreria esterna.

## Funzioni
- 10 tracce / 16 step
- 4 pattern + pattern chain in playback
- Web Audio scheduler
- velocity, probability, microtiming, swing, humanize
- sample WAV/MP3/OGG + waveform
- pitch, decay, filtro, volume, pan, send
- mute/solo
- reverb, delay, compressor
- undo/redo
- salvataggio IndexedDB
- export JSON, MIDI, WAV

## GitHub Pages
Carica questi file nella root del repository. Poi Settings > Pages > Deploy from a branch > main > /(root).

Per test locale usa un server HTTP, ad esempio `python -m http.server 8000`.
