# Web Drum Machine V2

Prototipo serio e **100% statico**, pensato per GitHub Pages.

## Funzioni
- 10 tracce / 16 step
- Web Audio API con synth drum built-in
- caricamento locale di WAV / MP3 / OGG
- waveform del sample
- pitch, decay, filtro, pan e send per traccia
- velocity / probability / microtiming per step
- swing + humanize
- randomizer
- mute all
- reverb, delay e compressor sul bus master
- pattern 1–4
- pattern chain
- salvataggio/caricamento JSON
- export MIDI
- export WAV tramite OfflineAudioContext
- nessun backend e nessuna libreria esterna

## GitHub Pages
Carica `index.html` in un repository e attiva:

**Settings → Pages → Deploy from a branch → main → /(root)**

## Nota sui sample
I sample caricati vengono decodificati **solo nel browser** e non vengono inviati a un server. Il JSON salva il pattern e i parametri, non il contenuto binario dei sample: dopo aver ricaricato un JSON, gli eventuali sample custom vanno ricaricati.

## Struttura
```text
web-drum-machine-v2/
├── index.html
└── README.md
```
