# Web Drum Machine

Prototipo statico di una drum machine web-based, senza backend e senza dipendenze esterne.

## Avvio locale
Apri `index.html` in un browser moderno. Per alcune funzioni audio il browser potrebbe richiedere un click sulla pagina.

## Pubblicazione su GitHub Pages
1. Crea un repository GitHub, ad esempio `web-drum-machine`.
2. Carica `index.html`.
3. Vai in **Settings → Pages**.
4. In **Build and deployment**, scegli **Deploy from a branch**.
5. Seleziona `main` e `/ (root)`, poi salva.
6. GitHub pubblicherà automaticamente il sito.

## Cosa include
- 10 tracce / 16 step
- Play / Stop
- BPM e swing
- Mute / Solo
- Volume per traccia
- Kick, snare, clap, hi-hat e percussioni sintetizzati con Web Audio API
- Velocity, probability e microtiming per step
- Pitch e decay per traccia
- Randomize
- Salvataggio/caricamento del pattern con localStorage
- Layout responsive

## Prossimi passi consigliati
- upload e gestione di sample WAV/MP3
- vero motore di scheduling look-ahead
- export WAV con OfflineAudioContext
- delay/reverb reali
- pattern chaining
- MIDI input/output
- salvataggio dei pattern come JSON
