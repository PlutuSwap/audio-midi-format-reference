# Audio-to-MIDI Format Reference

A small, reusable reference for checking whether an audio file fits FIELDNOTE's browser-based MP3-to-MIDI tool before you try a conversion.

## Current input support

| Input | Accepted | File limit | Duration limit | Processing | Output |
|---|---|---|---|---|---|
| MP3 (`.mp3`) | Yes | 25 MB | 60 seconds | In the browser on your device | Standard MIDI (`.mid`) |
| WAV (`.wav`) | Yes | 25 MB | 60 seconds | In the browser on your device | Standard MIDI (`.mid`) |
| FLAC (`.flac`) | No | — | — | Not applicable | — |
| M4A (`.m4a`) | No | — | — | Not applicable | — |
| OGG (`.ogg`) | No | — | — | Not applicable | — |
| AAC (`.aac`) | No | — | — | Not applicable | — |
| AIFF (`.aiff`) | No | — | — | Not applicable | — |
| Video containers | No | — | — | Not applicable | — |

The support table describes FIELDNOTE's current page, not universal browser or audio-format compatibility. Recheck the live page before relying on it.

## Quick preflight checklist

- Use one MP3 or WAV file.
- Keep it at or below 25 MB and 60 seconds.
- Choose **Melody** for a single-note-at-a-time sketch; choose **Auto** when you want overlapping notes retained.
- Treat the MIDI as an experimental draft. Listen to it and review the notes in a MIDI editor before using it in a project.
- The tool page says the selected audio is decoded and analyzed locally in the browser and is not uploaded.

## What this reference does not claim

This is a format and workflow reference, not a benchmark. It does not claim transcription accuracy, note-hit rate, or suitability for any particular recording.

## Sources

- [FIELDNOTE audio-to-MIDI tool](https://midifromsound.com/)
- [FIELDNOTE privacy page](https://midifromsound.com/privacy.html)

The facts above are transcribed from those pages and the live tool's stated upload controls. If the live tool changes, update this reference.
