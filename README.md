# A-Level Music Technology (Component 4): Audio Editing

Interactive learning labs, revision cheatsheets, and a terminology flashcard game for **Pearson Edexcel A-Level Music Technology (9MT0/04) — Component 4: Producing and Analysing**.

Live site: **https://audioediting.rjcaudio.co.uk**

## Included Resources (`public/`)

| Page | Description |
| :--- | :--- |
| `/` (`index.html`) | Main Component 4 Audio Editing Hub (workflow, Web Audio labs, AoS 1–3 theory, mark-scheme terminology, exam practice) |
| `/bass_di_amp_phase_alignment` | Scenario 1: Bass Guitar DI + Amp Phase Alignment Lab (sample-level waveform + comb-filtering frequency plot + Web Audio bass) |
| `/drum_phase_alignment` | Scenario 2: Drum Kit Phase (Snare Top/Bottom 180° polarity + Overhead distance delay) |
| `/vocal_comping_crossfades` | Scenario 3: Logic Pro Quick Swipe Comping (4 Synth Takes + Metronome Click) |
| `/drum_time_correction` | Scenario 4: Drum Time-Correction, Transient Grid & Flex/Elastic Audio Algorithms |
| `/vocal_pitch_correction` | Scenario 5: Vocal Pitch Correction (Flex Pitch / Melodyne / Auto-Tune) & Formant Preservation |
| `/audio_editing_flashcards` | Interactive 16-card Terminology Flashcard Game (categories, 3D flip, mastery & streak tracker) |

## Printable Revision Sheet (`docs/`)

- `docs/audio_editing_component4_cheatsheet.md` — Section A practical DAW checklist, AoS 1–3 summary, and common mark-loss pitfalls.

## Deployment

Deployed to Cloudflare Workers Static Assets (`audio-editing`) and served at `https://audioediting.rjcaudio.co.uk`:

```bash
npx wrangler deploy
```
