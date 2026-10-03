# Fretline 🎸

Learn guitar by playing. Fretline listens through your microphone and tells you, note by note and chord by chord, whether you played it right.

**Live app:** [https://rahul7387.github.io/guitar-learning-app/](https://rahul7387.github.io/guitar-learning-app/)

## What's inside

- **Lessons**: 30 lessons from beginner to expert: open strings, first chords, scales, barre chords, seventh chords, arpeggios and speed.
- **Songs**: public-domain melodies and chord songs, raag melodies (Yaman, Bhairavi, Kafi, Khamaj, Bhupali), film-style guitar exercises and filmi jam tracks.
- **Finger practice**: 18 warm-ups and drills with the finger number on every note.
- **Chords**: 17 chord types in all 12 keys, up to three shapes each.
- **Scales**: 12 scales in every key, mapped across the neck by position.
- **Create**: build your own mixes of chords and scale runs, your own finger exercises, and add songs in sargam, note names or tab.
- **Backing band**: drums (pop, rock, ballad, shuffle, waltz, disco, keherwa, dadra, qawwali, bhangra, garba), bass, keys and flute.
- **Listen first**: hear any piece before you play it, at any speed.
- **Tuner** with a live fretboard view.

## Install on Android

1. Open https://rahul7387.github.io/guitar-learning-app/ in Chrome.
2. Tap the menu (three dots), then **Install app** (or **Add to Home screen**).
3. Open Fretline from your home screen. It runs full screen and works offline after the first visit.

Allow the microphone when asked. Use headphones when the band plays notes, so the mic hears only your guitar.

## Your data

Progress, saved practice, songs and settings are stored in your browser on your device. Use **Create → Your data → Download a backup** to keep a copy, and **Restore from a backup** to move it to another device. Nothing is uploaded: sound from the microphone is analysed on your device and never leaves it.

## Run it yourself

It's a single static page with no build step. Serve the folder over **https** (the microphone needs a secure page), or locally:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Music credits

Built-in melodies are public domain (traditional tunes, Beethoven, Pachelbel, Petzold and others). Raag melodies, film-style exercises and jam tracks are original to this app.
