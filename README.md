# COSMIC DRIFT 🌌

## Project vision

An evolving, hypnotic ambient-techno composition built in **Cardinal inside Cubase**.

Inspired by the atmosphere of deep, organic, melancholic, spacious ambient techno (reference: Izhevski), without copying a specific track.

**Goal:** Cardinal autonomously generates the harmonic, melodic, bass and atmospheric arrangement of a full track. Kick and percussion are added separately in Cubase.

This repository is a **music-production notebook, not a software project**. It holds arrangement ideas, patch notes, module settings and decisions.

## Working parameters (draft)

| Parameter | Initial idea |
| --- | --- |
| DAW | Cubase |
| Modular instrument | Cardinal |
| Tempo | 118 BPM |
| Meter | 4/4 |
| Tonal center | D minor |
| Length | 128 bars (approx. 8:41 at 118 BPM) |
| Status | Planning — not yet patched or tested |

## Musical systems

1. **Evolving Chord Engine** — long, warm chords, changing voicings, slow filter and timbral motion.
2. **Polyrhythmic Chord Pulses** — short chord stabs following interacting 5-step / 7-step patterns against the regular 4/4 pulse.
3. **Sub Engine** — warm, monophonic sub that follows the chord roots and leaves room for the Cubase kick.
4. **Generative Space Arpeggios** — sparse, probability-controlled, harmonically constrained notes sent into delay and reverb.
5. **Slow Modulation Network** — multi-timescale modulation controlling timbre, activity, stereo movement and effects.

An additional **Master Arrangement Brain** reads or follows Cubase song position and controls long-form changes in the layers.

## Harmonic sketch (provisional)

An eight-bar cycle with two bars per chord:

| Bars of cycle | Chord | Sub root |
| --- | --- | --- |
| 1–2 | Dm9 (D F A C E) | D |
| 3–4 | B♭maj7(#11) (B♭ D F A E) | B♭ |
| 5–6 | Fmaj9 (F A C E G) | F |
| 7–8 | Cadd9 (C E G D) | C |

Not every voice should play on every iteration. Octaves, inversions, and occasional chord-tone omissions can evolve over time. Random notes must be constrained to the active harmonic context.

## Song structure — version 0.1

| Bars | Section | Active layers and movement | Intended energy |
| --- | --- | --- | --- |
| 1–16 | **Intro / Arrival** | Space drone, filtered evolving pad, wide tails; no or minimal sub | Very low |
| 17–32 | **Emergence** | Sub gradually enters; first quiet rhythmic chord pulses | Low → medium |
| 33–64 | **Hypnotic Flow I** | Chords, sub, interlocking polyrhythms; occasional sparse arpeggio | Medium, steady |
| 65–80 | **Breakdown / Weightlessness** | Sub and stabs recede; suspended chords, noise, delay/reverb tails | Low |
| 81–112 | **Hypnotic Flow II** | Return with changed voicings, evolving arpeggio density and richer modulation | Medium → high |
| 113–128 | **Outro / Dissolve** | Gradual reduction to pad and ambient tails | High → zero |

**Important:** this is a starting arrangement, not a locked composition. Transitions should be gradual and musical; changes can begin before section boundaries.

## Arrangement control principles

- **Macro modulation:** section-dependent layer density, filter brightness, harmonic tension, sub level, delay/reverb send and stereo motion across tens of bars.
- **Micro modulation:** continuous slow LFOs, probability, subtle timing changes and controlled random modulation within each section.
- **Repeatability:** make the musical arrangement deterministic where possible; record generative performances as audio in Cubase when a specific take should be retained.
- **Dynamics:** maintain space for an externally programmed kick and percussion; avoid permanently dense sub or chords.
- **Transitions:** use crossfades, slew and envelopes rather than abruptly gating all layers.

## Planned build order

- [ ] Verify Cardinal plugin variant, installed module availability and Cubase host sync
- [ ] Build a single warm chord voice and modulation
- [ ] Add an 8-bar harmonic progression and chord voicings
- [ ] Add monophonic root-following sub
- [ ] Add polyrhythmic chord stabs
- [ ] Add sparse harmonic arpeggios
- [ ] Add long-form arrangement controls by Cubase song position
- [ ] Route and record stems or layers in Cubase
- [ ] Refine transitions, dynamics and musicality by listening

## Working notes

- **Confirmed intention:** Cardinal handles the harmonic/atmospheric track; kick and percussion remain in Cubase.
- **To verify during patching:** exact installed module names, host-position handling, polyphonic routing and available outputs.
- **Creative priority:** hypnotic evolution and coherent harmonic movement over excessive random activity.
