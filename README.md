# CADTF Quiz Simulator

Static browser application for the 2026 provincial online Q&A simulation.

## Features

- Two-question exam simulation with official timing flow
- Audio recording for every question
- Browser speech recognition preview
- Mandatory local Whisper transcription after recording
- Standard-answer comparison and semantic scoring
- Fifty-question bank with non-repeating draw mode
- Local history with audio playback and report export
- Printable PDF analysis reports

The application is fully client-side. Recordings and records are stored in the
user's browser. Audio transcription and semantic scoring download models from
public model mirrors on first use and then rely on the browser cache.
