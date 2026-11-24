# A-Level Music Technology (9MT0/04) — Component 4: Audio Editing Cheatsheet

**Exam Context:** Component 4 (*Producing and Analysing*) is **35% of the A-Level** (105 marks, 2h 15m + 10m setup).  
Audio editing is assessed practically in **Section A** (DAW stems & exported WAVs) and analytically in **Section A/B** written questions.

---

## 1. Section A: Practical DAW Editing Checklist

- [ ] **Non-Destructive First:** Keep original stems untouched in the project/audio bin; use region edits, playlists, and Flex/Elastic markers rather than overwriting source files.
- [ ] **Top & Tail / Clean-Up:** Trim count-ins, headphone spill, breaths, and dead air. Cut at **zero-crossing points** (0 V) and add **5–15 ms fade-ins/fade-outs**.
- [ ] **Comping:** Assemble the best phrases across multiple takes. Place splice boundaries in natural pauses, level-match with **clip/region gain**, and bridge every edit with an **equal-power crossfade**.
- [ ] **Phase & Polarity (Multi-Mic / DI + Amp):**
  - Zoom to **sample level** and nudge/delay the earlier track so first positive transient peaks align.
  - Test **180° polarity inversion (Ø)** on opposite-facing mics (e.g., snare top vs. snare bottom) to remove **comb filtering**.
- [ ] **Timing & Quantisation:**
  - Choose the right Flex/Elastic Audio algorithm: **Rhythmic/Slicing** (drums), **Monophonic** (vocals/bass), **Polyphonic** (guitars/keys).
  - Avoid extreme stretching (>10–15%) that causes **pre-echo**, **flamming**, or metallic smearing.
- [ ] **Pitch Correction (Melodyne / VariAudio / Flex Pitch):**
  - Tune **pitch centre** without flattening natural **pitch drift/vibrato** (unless a robotic hard-tuned effect is specified).
  - Keep **formant preservation** ON for corrective edits to avoid "chipmunk" or "monster" artifacts.
- [ ] **Creative Edits (AoS 1):** Reverse audio swells (cymbals/reverb), rhythmic stutter/chopping, and pre-compression clip-gain levelling.
- [ ] **Export / Bounce Check:** Verify exact bar range, solo/mute states, sample rate/bit depth (apply **dither** if bouncing 24-bit down to 16-bit WAV), and listen back to the bounced file for clicks or cut-off tails.

---

## 2. Underpinning Theory (AoS 1, AoS 2 & AoS 3)

| Area | Key Concept | Exam Explanation |
| :--- | :--- | :--- |
| **AoS 1** | **Corrective vs. Creative** | Corrective fixes timing, tuning, phase, or noise; creative reshapes timbre/rhythm (reverse, stutter, formant shift). |
| **AoS 2** | **Sample Rate & Bit Depth** | Higher sample rate = finer time resolution for phase nudging & stretching. 24-bit = lower noise floor (~144 dB) when boosting quiet clips. |
| **AoS 2** | **Varispeed vs. Time-Stretch** | Varispeed links speed and pitch (+100% speed = +1 octave). Time-stretching decouples duration and pitch via FFT/granular processing. |
| **AoS 3** | **Tape Splicing → DAW** | Analogue tape editing was **destructive**: chinagraph pencil markings, 45°/90° splicing block, razor blade, and splicing tape (45° cut = physical crossfade). |

---

## 3. Common Mark-Loss Pitfalls to Avoid

1. **Audible clicks at edit points** → Always zoom in to zero crossings or add short crossfades.
2. **Volume dip mid-crossfade** → Switch from *linear* to *equal-power* crossfade for uncorrelated takes.
3. **Hollow/thin multi-mic drums or bass** → Check sample alignment and polarity inversion before reaching for EQ.
4. **Vague written terminology** → Write *"apply an equal-power crossfade at a zero-crossing point"* instead of *"smooth out the join"*.
