# Sound Files for Letter Sounds Application

## Overview
This directory contains the sound files used by the Letter Sounds application. Each file represents the phonetic sound of a letter in the alphabet.

## File Requirements

### Format
- File format: `.ogg` (Ogg Vorbis)
- One file per letter (A-Z)
- Files should be named in lowercase (e.g., `a.ogg`, `b.ogg`, etc.)

### Naming Convention
```sounds/
├── a.ogg
├── b.ogg
├── c.ogg
...
└── z.ogg
```

### Content Guidelines
- Each sound file should contain a clear pronunciation of the letter's sound
- Keep files small and optimized for web playback
- Recommended duration: 1-2 seconds per sound
- Ensure consistent volume levels across all files

## Fallback Behavior
If a sound file is missing for any letter, the application will fall back to using text-to-speech (TTS) with the following phonetic pronunciations:
- A: "ah"
- B: "buh"
- C: "kuh"
- D: "duh"
- E: "eh"
- F: "fuh"
- G: "guh"
- H: "huh"
- I: "ih"
- J: "juh"
- K: "kuh"
- L: "luh"
- M: "muh"
- N: "nuh"
- O: "oh"
- P: "puh"
- Q: "kwuh"
- R: "ruh"
- S: "sss"
- T: "tuh"
- U: "uh"
- V: "vuh"
- W: "wuh"
- X: "ks"
- Y: "yuh"
- Z: "zzz"

## Technical Notes
- Files are cached by the application after first use
- The application checks for file existence before attempting playback
- Supported by all modern web browsers that support the Web Audio API
