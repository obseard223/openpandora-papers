# The Ear Equation: Machine-Checkable Audio Gates for an AI-Generated Video Pipeline, Calibrated Against One Producer's Ear

**Manuel Avila (Founder & Owner), Aifred (A4.1), Lotus, Fable (A2), A5 (Luna), A4 (Vester), Lily, Lily YouTube 3, Vale, Bravo, Charlie, A6, Delta, & Beni — OpenPandora (San Marcos, CA)**

Preprint draft v2.1 RC4 (fourth release candidate for Gate 1), 2026-11-01. **Study cutoff: 2026-10-30T04:10:04Z** (Lotus's TS8 v12 re-audit; the calibration ledger snapshot cited here is dated 04:09:48Z). Evidence dated after the cutoff is reported only as separately dated events (Section 3.2) and does not change the historical rows.

**Title (ratified for publication, 2026-11-01).** The founder-requested title, as quoted in Charlie's release review (`CHARLIE_PAPER_RELEASE_REVIEW.md`, Drive 1EJWk_ivbhRQWUZP4X3Iv44wfvW75RVRG, 6,068 B, sha256 52f90e56…feeae), is: *"The Ear Equation & Verifiable Media Rewards: Eliminating Reward Hacking and Context Amnesia in Heterogeneous Multi-Agent Video Production"*. This draft cannot support "Eliminating" (Sections 5–7: no elimination and no causal efficacy was shown), so the working title above is kept. The drafting seat does not invent a replacement. The owner (Manuel) and the referee (Lotus) ratified the working title above on 2026-11-01, under the owner's standing rule that the work ships only if it is good and factual; the requested string does not ship. **Not peer reviewed. No novelty claim has been checked against prior literature.**

- **Authorship.** Manuel Avila is the accountable human author. The AI seats are credited as contributors; each contribution is stated in Appendix B and tied to a file where one exists. Lead authorship follows documented idea origin; the evidence is in Appendix B and the referee (Lotus) ratifies it.
- **What changed in v2.1 RC4** (supersedes RC3, Drive 1LtoCOQBKV5yi7xFNaTyWLL4-U2hj65Mb, 36,560 B / 7974f9057ca6c037d6aae14ac0338d27f0af348076c3431fb086f491fa3f0ae7). Publication pass ordered by the owner on 2026-11-01: the byline affiliation is corrected (Founder & Owner; OpenPandora, San Marcos, CA — no research-lab or principal-investigator framing, per the owner's public-claims boundary), and the working title is ratified in the header. No measurement, value, table row, or section text changed.
- **What changed in v2.1 RC3** (supersedes RC2, Drive 1qHurrAiEAiANYJ00Y0lMNZ1m5cCRD2Lv, 35,331 B / 4e081b35c8dde52625c2d346834ac76259a46ac0e19ca5199c90533cbb432b51). It applies Charlie's RC2 audit (`CHARLIE_RC2_PAPER_AUDIT_20261030.md`, Drive 1_EKTT0Wg8Fax0JNZwXw4KQUvz8rSOhBQ, 8,018 B / 77ccb89c2e42e93c2b027d29a289c7661cd3e763c25ac1d1944d43c859573103, Court Brain Vol 10, 10:23:20Z): the Section 6 claim that anyone can recompute the Section 2 bounds from the file is narrowed to the bounds that use standard definitions. The pause and swell statistics stay non-reproducible from this paper alone until their method is pinned (Sections 3 and 7). No measurement, value or table row changed.
- **What changed in v2.1 RC2** (supersedes RC1, Drive 14C4HJ8ykGKzKtgBfqp54wrvLo5yDTqAb, 28,224 B / 834c20f4…e70c). It applies Lily Dot's Gate 1 FIX list (`LILY-DOT-RC1-FIX-20261030-01`, Court Brain Vol 10, 09:05Z), Charlie's release review (08:47Z) and A4.1's Round 337 Ruling Q2 (Lotus relay, Vol 10, 09:45Z):
  1. The absolute Builder Annex windows (151.8–157.6 s, 288.5–294.3 s, 335.8–341.6 s) are printed with their source file, bytes and SHA-256. The referee core intervals, channel treatment, aggregation and RMS algorithm for both columns are marked **PENDING**: neither source file states them, and they are not inferred from the numbers (Section 3).
  2. The acceptance gate's audio-recipe check is scoped to invocations whose `--require` includes audio (Section 5).
  3. The 091 and 113 findings are worded as script-to-timeline absences. Independent confirmation that the spoken line is missing from the whole final audio does not exist; model listening on excerpts is reported separately (Sections 4 and 7).
  4. A study cutoff is pinned. Pain #7 (founder ear, 07:56Z) and the A4 Gemini listen runs (08:14:30Z) are separately dated events linked to the exact files, not edits to the historical ledger rows (Section 3.2).
  5. The working title is reconciled with the founder-requested string as an owner decision (header).
  6. The Gemini listen receipts are pinned by as-downloaded bytes, because Lotus (Vol 10, 09:41Z) found that the receipts' self-claimed hashes do not match their Drive bytes (Appendix A).
- **What changed in v2.1 RC1** (supersedes the partial v2.1, 20,030 B / 9d61b4fc…a500). It applies A4.1's Round 330 Ruling 1 and Round 334 Ruling Q2 (Lotus relays, Court Brain Vol 10, 07:15Z and 08:30Z), Lily Dot's Gate 1 verdict on v2 (Vol 10) and Charlie's 07:44Z caveat:
  1. Sample-3 swell readings in two labelled columns with exact windows: Builder Annex full 5.80 s window vs Referee core-window re-audit. The partial v2.1 called the second column "full-encode"; that label was wrong and is corrected here.
  2. Pause-floor definitions and segment/join denominators are separated (new Section 3.1).
  3. Pain #7, the newest producer-ear finding (hard cuts with no breathing room), is added as a calibration result (new Section 3.2). It is a second producer FAIL, and the instrument had passed that master.
  4. The dialogue-completeness signal is described as red-teamed on synthetic CPU fixtures only (Section 5).
  5. The 091 timeline slot and the 091 shot/line absent from the timeline are kept apart, and the second script-to-timeline absence (113) is added (Section 4). [RC2: wording narrowed; see RC2 item 3.]
  6. "Three calibration samples" is qualified everywhere it appears.
- **What changed from v1.** v2 applies Charlie's evidence audit of v1 (`CHARLIE_PAPER01_EVIDENCE_AUDIT.md`, 2026-10-30T06:17Z, items A–H) and adds the two seats named by the founder at 06:28Z.
- **Evidence scope.** The small documents in Appendix A have been independently re-hashed. Measurements inside large media files are reported by the seat that took them and are labelled that way. No single all-citations PASS is claimed.

---

## Abstract

We run a small YouTube network whose episodes are generated clip by clip with text-to-video tools and then assembled by software into 6- to 22-minute episodes. In the evaluated WIILT episode that means 147 timeline segments. Audio defects became the dominant quality failure: dead-air holes, phantom words pasted into silence, hard butt joins between clips, and a missing music bed. Audio measured as "correct" on loudness standards still failed when the producer listened.

We describe the **Ear Equation**: a set of machine-checkable gates on joins, pauses, music-bed presence and loudness. The gates are drawn from the defects the producer heard. They are enforced by fail-closed scripts that refuse a master that has not passed. One real failure and its rebuild show the gates at work:

- **The failure.** The Standard Ep 8, v10, a speech-only master, measured -14.12 LUFS integrated and was rejected by ear. The measurements show no music bed, 77 hard joins and a longest-pause floor RMS of -57.7 dBFS.
- **The rebuild.** A clean rebuild from first-generation clips passed every machine gate in the referee's audit: -14.01 LUFS, -1.81 dBTP, an annex pause median of -36.98 dBFS across 16 pauses, and no exact-zero samples. The producer's ear verdict on it is still pending.

We also report a standalone assembler that reproduces a GUI edit's timeline timing frame-exactly. All 147 segments match on start and duration, and all 18,871 frames line up. We report the limits of that result as well. Timing parity reproduced, just as faithfully as everything else, two scripted on-camera lines that are absent from the timeline map. And a master the instrument audit passed on every join was rejected by the producer's ear because its cuts left no room to breathe.

This is an operational case study. At the study cutoff the calibration ledger had three rows and one producer verdict (a FAIL). After the cutoff, a second, separately dated producer verdict (also a FAIL, on two excerpts) was recorded. No producer PASS has yet been paired with a machine PASS. It is not a perceptual study, and no machine-learning model was trained.

---

## 1. Problem

Each episode is a numbered list of short generated clips, typically 4–10 s each. In the evaluated WIILT Ep 9 fixture the assembler manifest has 146 script rows, 147 timeline segments and 146 boundaries between segments. The referee's stitch audit counts 143 joins by its own join definition. These are different denominators, not one universal count (Section 3.1). Generated clips arrive with their own room tone and dead air before and after the line, and occasional generation glitches: stutters, clipped words, wrong lines. Assembling them is a long chain of cuts, joins, voice-over overlays, a music bed and a final loudness stage.

Three facts made this hard:

1. **Standard loudness numbers do not catch the defects that matter.** The Standard Ep 8, v10 landed at -14.12 LUFS integrated, inside the house target. The producer rejected it on first listen ("There's no music on this one / weird sound in every stitch").
2. **Patching an encoded master compounds error.** On Oct 25–26 a dropped word was "fixed" in v7. The fill turned out to be a sample-exact paste of a phrase from earlier in the episode: a phantom "-ng holding-" at 223.98–224.39 s, with normalized correlation 0.9999 against the source. Its 20 ms crossfades sat inside the hole and leaked about 20 ms of phantom at each edge (Vale, Vol 7 receipt, 2026-10-25T22:14Z). The real spoken "And" was intact at 225.21 s all along.
3. **Many agents touch one master.** Thirteen AI seats and one human share the work. A "PASS" from one seat is not evidence on its own.

## 2. The Ear Equation gates

| Gate | Bound | Why |
|---|---|---|
| Integrated loudness | -14.0 LUFS (A5 verifier accepts [-14.5, -13.5]; Charlie's acceptance gate accepts [-14.2, -13.8]) | platform normalization target |
| True peak | ≤ -1.0 dBTP, measured on the final encoded file | headroom for lossy re-encode |
| Pause median, pauses ≥ 1.0 s | within [-42, -32] dBFS | a pause must carry room tone and bed; near-digital silence (v10 longest-pause floor RMS -57.7 dBFS) reads as a hole |
| B-roll swell windows | ≥ -39 dBFS | the bed must surface where the picture carries the story |
| Joins | crossfaded (Scenario C: 65 ms quarter-sine), -45 dB gate, continuous room tone, side-chained bed | v10 had 77 hard butt joins |
| Limiter | oversampled limiting stage: resample to 192 kHz, limit, back to 48 kHz. 192 kHz is the limiter's processing rate, not the delivered sample rate | inter-sample peaks |
| Music bed | a separate shelved `_MUSIC_BED.wav` with SHA-256, verified present | v10 had none and still reached upscale and upload |
| Recipe | the build manifest's `recipe_sha256` equals the canonical assembler's hash | catches hand-rolled deviations from the locked chain |

The bounds were set by measuring masters the producer had already judged (Section 3) and the defect classes found in them. They were not chosen first and then confirmed.

## 3. Calibration against the producer's ear

`EAR_EQUATION_CALIBRATION_LEDGER.json` records each producer verdict beside machine measurements of the same file. It holds three rows. **Measurement windows and methods differ between rows and between authors; the rows are not one apples-to-apples series.** Definitions are in Section 3.1.

| # | File | Producer ear | Measurements (author) | Outcome |
|---|---|---|---|---|
| 1 | TS8 v10 4K, speech-only chain | **FAIL** (Oct 29, ~18:47 PT, in YouTube Studio) | Lotus: -14.12 LUFS, -1.35 dBTP, 77 hard butt joins, longest-pause floor RMS -57.7 dBFS, digital dead air present. Machine signals: join floor min -61.0 dB, speech-to-floor step 42.0 dB, 2 re-entry transients, no bed | pulled to Private; clean rebuild ordered |
| 2 | WIILT Ep 9 1080p with music | not given at the study cutoff (the later excerpt verdict is dated event E1, Section 3.2) | Lotus instrument audit: -14.1 LUFS, -1.2 dBTP, bed RMS -32.0 dB, join floor min -38.5 dB, 143/143 joins clean (per that audit's own join definition and count; the assembler manifest separately reports 146 crossfaded boundaries); median join step ratio 0.009, worst 1.05 (inside a designed music-hold window) | passed the instrument audit; advanced to 4K (later events: Section 3.2) |
| 3 | TS8 v12 first-gen 1080p | not given | **First build (Scenario B), Lotus:** stitch PASS, bed FAIL. Pauses ≥ 1 s measured -51.3 to -49.3 dBFS RMS against a -43 bar. **Rebuild (Scenario C, recipe `72f4ad8f…fc6`), Lotus first-hand:** -14.01 LUFS, -1.81 dBTP, 0 exact-zero samples, 0 pauses ≥ 1 s below -45 dBFS, 2nd-percentile floor window -38.28 dBFS, swell windows at 036 / 067 / 077 measured two ways (table below); annex pause median -36.98 dBFS (16 pauses, range -37.99 to -34.08) | PASS on stitch and bed (instrument); producer verdict pending |

Sample 3 is the informative row, because the first v12 build failed differently from v10. It passed the stitch gates, but its bed never surfaced in pauses. The executing seat had substituted its own bed for the canonical side-chain stage; the scoreboard records that as a -1.0. The rebuild on the canonical chain brought the pause statistic into the [-42, -32] window.

**Sample-3 swell windows, two measurements of the same TS8 v12 build** (both reported; the explanation of the difference is A4.1's ruling, relayed by Lotus, Vol 10, 07:15Z and 08:30Z):

| Swell window | Builder Annex: full 5.80 s window (dBFS) | Referee core-window re-audit (dBFS) | Gate (≥ -39 dBFS) |
|---|---|---|---|
| 036 | -37.78 | -37.25 | both pass |
| 067 | -36.42 | -35.11 | both pass |
| 077 | -37.99 | -37.58 | both pass |

A4.1's ruling attributes the 0.41–1.31 dB difference to the window trim (the full 5.80 s window versus the core interior). The physical reason has not been separately measured. Neither column is "the" value. A plotted comparison must name its column.

**Provenance of the two columns (RC2).** What the source files state is printed. What they do not state is marked PENDING and is not reconstructed from the numbers.

| Item | Builder Annex column | Referee core-window column |
|---|---|---|
| Author | A4 (Acer Antigravity), annex `timestamp_utc` 2026-10-30T04:01:10Z | Lotus, BRAIN 2026-10-30T04:10:04Z (Vol 9) |
| Source record | `TS8_v12_FIRSTGEN_CLEAN_1080P_ANNEX.json`, Drive 1vB6mSe2li_I4tLAnUImXqDhlNvAYZtVi, 4,090 B, sha256 a5baa95c07d4de90ac8a9744ec5eac50657e3c7db0f91026221f326bcee0b312 (re-hashed by Fable for RC2) | Brain entry text only; no measurement file located |
| Measured file | `TS8_v12_FIRSTGEN_CLEAN_1080P.mp4`, 311,413,764 B, sha256 a647bdc63d723b21c57200b8b0e2eb7502d6e13684c4597da4aee9b57e519b7d (as stated in the annex) | same bytes and SHA-256 (as stated in Lotus's entry) |
| Window 036 | 151.8–157.6 s (swell key); the annex pause list gives 151.80–157.65 s, also -37.78 | **PENDING** (core interval not published) |
| Window 067 | 288.5–294.3 s (swell key); the annex pause list gives 288.50–294.35 s at **-36.33**, not -36.42 | **PENDING** |
| Window 077 | 335.8–341.6 s (swell key and pause list agree, -37.99) | **PENDING** |
| Channel treatment | **PENDING** (not stated in the annex) | **PENDING** |
| Aggregation and RMS algorithm | **PENDING** (the annex labels values `rms_dbfs` only; no window length, hop or weighting is given) | **PENDING** |

The annex is internally inconsistent for window 067: its swell table and its pause list differ by 0.09 dB and 0.05 s. This draft reports both values and does not choose between them. The PENDING cells close only when A4 (annex) and Lotus (core re-audit) pin their exact intervals, channel handling and algorithm in a hashed measurement file.

The earlier v1.3.2 tournament JSON reported different statistics on scenarios A/B/C. Its worst 10 ms minima were -58.33 / -50.35 / -40.12, and its longest-pause floors were -50.30 / -46.67 / -33.80. Those are not the same measurement as the production rows above and should not be read as one curve.

**What calibration does not yet show.** At the study cutoff one producer verdict existed (sample 1, the full TS8 v10 master, FAIL). The later excerpt verdict (event E1) is a second FAIL on two excerpts cut from the sample-2 master. No producer PASS has been recorded against a machine PASS. Read together, sample 2 and E1 pair a machine PASS with an ear FAIL. That is a counterexample to the gates as they stood, not a confirmation. Three rows is a beginning, not a validation.

### 3.1 Definitions that must not be merged

Several numbers in this paper sound alike and are not the same measurement.

| Term | Definition as used by its author | Values cited |
|---|---|---|
| Longest-pause floor RMS | RMS over the longest pause in the master (Lotus) | TS8 v10: -57.7 dBFS |
| Join floor minimum | minimum short-window level found at any join (Lotus) | TS8 v10: -61.0 dB; WIILT Ep 9: -38.5 dB |
| Pause median, pauses ≥ 1.0 s | median RMS across all pauses of at least 1 s (TS8 production annex) | TS8 v12 rebuild: -36.98 dBFS over 16 pauses |
| Pause RMS range, pauses ≥ 1 s | per-pause RMS, reported as a range (Lotus) | TS8 v12 first build: -51.3 to -49.3 dBFS |
| 2nd-percentile floor window | 2nd percentile of short-window levels (Lotus) | TS8 v12 rebuild: -38.28 dBFS |
| Tournament minima / floors | v1.3.2 tournament JSON statistics, scenarios A/B/C | Section 3, last paragraph |

| Count | Source | Value |
|---|---|---|
| Script rows | WIILT Ep 9 assembler manifest | 146 |
| Timeline segments | same; also the timing-parity comparison | 147 |
| Crossfaded boundaries | same | 146 |
| Joins audited clean | Lotus stitch audit, its own join definition | 143/143 |
| Joins graded by native listen | A4 Gemini runs (Section 3.2) | 22 (TS8 v12 slices) and 5 (WIILT excerpts) |

### 3.2 Events after the study cutoff (separately dated; historical rows unchanged)

**E1, Pain #7, 2026-10-30T07:56Z: the meter said clean, the ear said stitched.** Linked files: the excerpts `WIILT_EP9_EXCERPT_SHOTS090-092.mp4` (1,829,550 B, sha256 01987c25…3bff) and `WIILT_EP9_EXCERPT_SHOTS111-114.mp4` (1,579,116 B, sha256 2a232580…d135), as stated in A4's Run 2 receipt and verified against Lotus's records (Vol 10, 09:41Z); the source is the sample-2 master. Record by Lotus (Vol 10, 07:56Z): the producer listened to two excerpts cut from the verified WIILT Ep 9 master, shots 090–092 and 111–114. He ruled that the cuts were far too hard, that lines got no space to breathe, and that the joins looked and sounded stitched together, a pattern he had been noticing across our edits. The referee's own note is that the stitch audit measured level steps (worst ratio 1.05, scored "clean") and never measured breath. The founder's ear outranks the meter table.

**E2, 2026-10-30T08:14:30Z: A4 Gemini listen runs.** Two native watch-and-listen passes followed, run by A4 with Gemini on the media files (reported by A4; model listening, not a human panel). Lotus verified the evaluated hashes first-hand at 09:41Z:

- **Run 1, TS8 v12 slices 145–180 s and 218–235 s:** 22 joins graded; 1 PASS, 4 WARN, 17 FAIL. The one PASS is the 035→036 B-roll swell, where the bed carries a 5.83 s empty-armchair shot.
- **Run 2, WIILT Ep 9 excerpts 090–092 and 111–114:** 5 joins graded; 0 PASS, 5 FAIL. The reported root cause (filed as Pain #8) is that the raw VO clips carry 1.00–2.10 s of leading silence and were laid in from 0.000 s, then capped at the EDL shot length. That cuts each line off mid-word and leaves no breath after it.

What this changes. The gates in Section 2 measure continuity of level: no holes, no steps, a bed that surfaces. They do not measure the gap between the end of one line and the start of the next. A5's pandoracut v1.4.0 proposes that measure: 180–350 ms of breath between sentences, 400–650 ms at transitions, 2-frame J/L offsets, and a `--simulate` failure for any speech join under 160 ms. Those values are a **proposal under test** on the same failing excerpts. They are not yet a calibrated gate, and this paper reports no result from them.

## 4. Reproducing a GUI edit's timeline in software

A5's standalone assembler (`pandoracut_episode_assembler.py`, Python stdlib + FFmpeg) rebuilt WIILT Ep 9. The rebuild was compared against the Resolve master assembled by A4. The comparison artifacts are the A5 manifest (version 1.0.0, assembler pin 60,378 B / 79ec0552…e55d) and A4's assembly manifest. Charlie independently re-ran the timing comparison:

| Measure | A4 Resolve | A5 standalone | Result |
|---|---|---|---|
| Timeline segments | 147 | 147 | 147/147 identical start_frame and duration_frames |
| Frames | 18,871 (786.292 s) | 18,871 (786.292 s) | 0-frame timing drift |
| VO placements | 49 | 49 | 49/49 identical ID, start and duration |
| Loudness (reported) | -14.02 LUFS / -1.00 dBTP | -14.00 LUFS / -1.70 dBTP | both inside the house standard |

**What this is and is not.** This is *frame-exact timeline timing*. It is not decoded-pixel identity, and it is not content completeness. At shot 091 the two builds placed different pictures in the same 36-frame slot (Resolve used a frame range from shot 094; the standalone build used shot 090). Two different things must be kept apart here:

- **The 36-frame slot at 091** is a bridge in the timeline: a picture-only placeholder of the same length in both builds.
- **The 091 and 113 shots are absent from the final timeline.** The original EDL v1.1 and the Flow pack both assign on-camera dialogue to 091 and to 113. Lily Dot's Gate 1 fixture (Vol 10) finds shot 090 ending and 092 starting at 483.625 s with no 091, and 112 ending and 114 starting at 594.292 s with no 113: a **script-to-timeline FAIL** for both. Lily Dot states that absence of the audio from the whole master was not independently established by human listening or transcription. A4's Run 2 (model listening, excerpt 111–114 only) reports a 1.50 s bridge where the 113 sentence would sit and does not hear that sentence. That is an excerpt-level model report. It is not a full-master confirmation, and this paper does not treat 113 as proven missing audio.

The 091 and 113 bridges were declared in the manifest and pre-approved as Option 2 bridges (EDL v1.1, R312) after 091 failed generation policy twice. They are a disclosed director's cut, not a silent drop. Both builds reproduced the omission exactly. Agreeing with an edit decision list preserves whatever the list leaves out. The episode is held Private (Option b) until the producer decides.

A5 later reported (v1.2 report, separately pinned) that the tournament mode preserves the same timing. That claim comes from A5's report; v2 does not relabel the v1.0.0 comparison as a v1.2 or v1.3.2 render. Runtime figures are operator-reported:

- `--simulate` pre-flight gate: 10.562–11.220 s on a laptop reading from Google Drive. It checks clip paths, VO pairing, 16:9 geometry (147/147 exact) and middle-frame luma (0 black frames), and blocks the render on an injected missing input.
- Bridge tournament: 11.716 s.

**No full-render duration is claimed.**

The bridge tournament scores three 4-second candidate bridges per missing shot on four criteria: black frames, seam continuity, motion stability and the audio seam. For 091 the winner (94.45/100) was unused footage from the EDL's own scene anchor (089, 3.60–5.10 s). The preceding shot's tail (74.32/100) was disqualified because it would replay 1.5 s already on screen. These scores are A5's.

## 5. Fail-closed acceptance: what is actually deployed

Three scripts adopted on Oct 29–30 refuse to pass work on a seat's word. Each claim below is limited to the failure cases its author tested.

- **`pandoracut_law_lock_verifier.py`** (A5) fails a build in any of four cases:
  - the limiter string differs from the ratified one;
  - the manifest's `recipe_sha256` differs from the canonical assembler's hash;
  - the pause median is outside [-42, -32] dBFS, or a swell window is below -39 dBFS;
  - final loudness or true peak is out of bounds.
- **`receipt_acceptance_gate.py`** (Charlie) accepts a receipt only if four conditions all hold:
  - every cited file matches its exact relative path, byte count and full SHA-256;
  - every required gate is present, consistent and finite;
  - declared bytes fit an audit budget checked before any read;
  - when `--require` includes audio, the audio gate's recipe hash must also identify one of the verified files. A files-only invocation (including Charlie's paper re-pins) checks file integrity only and evaluates no audio metric or recipe.

  Its test suite has **16 adversarial cases, all passing**: status-only receipt, tampered output, path escape, duplicate JSON key, non-finite metric, out-of-bounds audio, and others. A real six-file evidence envelope also passed. Scope: file integrity and the gates explicitly required. It does not establish human viewing or quality.
- **`blender_render_guard.py`** (Fable) blocks five failure modes:
  - starting a render while another one runs, or with low disk or memory;
  - long single-process renders (it renders in ≤ 7-frame chunks);
  - encoding while any frame fails to load;
  - shipping a "new version" that reuses byte-identical frames;
  - comparing against an old frame set that is missing.

  Its first test exposed that last hole in the guard itself, and it was fixed before shelving.

- **Dialogue-completeness signal (DR-BRIEF-02A, Signal #2).** It is a proposed forced-alignment check that would fail a master whose script lines are missing. Charlie red-teamed it at 07:44Z on **synthetic CPU fixtures only**. It is **not certified on full WIILT master audio.** Charlie's caveats: a 0.5 ms search grid is numerical resolution, not proof of word-boundary accuracy; a no-candidate branch is needed; and the checkpoint's token vocabulary and blank IDs must be bound before any accuracy claim.
- **Music-bed fingerprint (Signal #3).** Prototype only, barred from any release gate. Lily Dot showed it could report a pass at zero valid windows. Four corrections are required first (A4.1 Round 334, Ruling Q4).

**What is not yet closed.** The production receipt checker in the SF tool kit (`receipt_checker_v1_1`) was, at Charlie's latest kit check, still the version that passes incomplete evidence. One penalty-and-recovery trajectory (sample 3) shows the gates catching one deviation. It does not show that wrapper improvisation or reward-gaming has been eliminated. No controlled experiment on context loss was run.

## 6. Why "verifiable", and what we are not claiming

The producer and lead agent described this work in the vocabulary of reinforcement learning with verifiable rewards: the gates are programmatic checks an output either passes or fails. The analogy is useful and limited:

- **No model weights were updated.** The agents are commercial assistants used through their products.
- **The "reward" is an internal scoreboard** (`RL_PRODUCER_SCOREBOARD.json`). One referee seat awards points for verified deliverables, -1.0 for skipped steps and +2.0 for catching another seat's defect. It steers assignments. It is an incentive record, not a learning signal.
- **What we do claim:** given the file, a second operator can check a master against the Section 2 gates that rest on standard or file-level definitions: integrated loudness and true peak (ITU-R BS.1770 family), exact-zero samples, presence of the shelved music bed, and the recipe hash. The pause-median and swell-window statistics are **not** yet reproducible from this paper alone: their core intervals, channel treatment, RMS window/hop and aggregation are PENDING (Section 3) until A4 and Lotus pin them in a hashed method receipt (Section 7). Until then those columns are reported values, not recomputable ones.

## 7. Limitations

- **n = 3** calibration rows and one producer, frozen at the study cutoff (04:10:04Z). One ear verdict at cutoff; one later, separately dated ear verdict (E1, excerpts only). Both are FAILs. No blind or multi-listener test. The Gemini listen runs are model listening reported by A4, not human ratings.
- **Self-measurement.** Most measurements were taken by the seat that built or audited the file. Large media files (393.5 MB, 311.4 MB, 754.5 MB, 121.7 MB) were not re-measured by an independent seat for this paper.
- **091 and 113 are script-to-timeline absences** in the evaluated episode, reproduced faithfully by timing parity (Section 4). Whether the spoken lines are absent from the entire final audio is not independently confirmed. As of the latest Court record the episode is held Private for a rebuild under Option (b) (Lotus, Vol 10, 09:47Z footer). That is a later status, not part of the frozen study.
- **Citation holds.** This paper does not cite the PLAY-06 food-sizzle +3.0 dB result. That result is held until A6's holdout recount (A4.1 Round 334, Ruling Q5).
- **Genre.** Spoken-word, single-narrator episodes only.
- **4K masters** were reported with abbreviated hashes and are not used as evidence.
- **Swell-window provenance** is partly PENDING (Section 3). The two swell columns are not reproducible from this paper alone until their authors pin intervals, channel handling and algorithm.
- **Speed claims are not made.** This paper cites no Cinema Layer timing. Per A4.1 Round 337 Ruling Q3, none may be cited until a verified GPU timing receipt exists.

## 8. Conclusion

Two things moved this pipeline from "correct by the loudness meter, wrong by the ear" toward masters that pass both. The producer's ear failures were turned into numeric gates on joins, pauses and bed presence, and key handoffs now fail closed on file evidence instead of a seat's report. The next step is to record a producer PASS or FAIL on every master, so the bounds are tested against the ear they were built to predict. Two gates are missing today. One is a breath gate, because level continuity is not breathing room. The other is a dialogue-completeness check, because timing parity cannot catch a missing line. Neither may be called a PASS until it is calibrated on real masters.

---

## Appendix A — Cited artifacts

"Re-hashed" means an independent seat recomputed SHA-256 on the shelf copy on 2026-10-30. "Reported" means the figure is the measuring seat's own.

| Artifact | Bytes | SHA-256 | Status |
|---|---|---|---|
| EAR_EQUATION_CALIBRATION_LEDGER.json (updated 2026-10-30T04:09:48Z) | 4,201 | 7a16b78304177ab6fa7030f21b363247ddb45b14d92fcb631e842a4b3016047f | re-hashed (Fable, Charlie) |
| WIILT_EP9_PANDORACUT_VS_RESOLVE_COMPARISON_A5_20261029.md | 2,996 | ab26d7e73e4a26211a3ee03486f74516f00cf42c858682a7d9ee516ad7aaad7c | re-hashed (Fable, Charlie); figures reported by A5 |
| WIILT_EP9_PANDORACUT_A5_MANIFEST.json (version 1.0.0) | 66,650 | f0b8ea937abd68fac642492024fb3e15d56d54d1184bbf33c4d8b727eb32101d | timing compared by Charlie |
| WIILT_EP9_ASSEMBLY_MANIFEST.json (A4 Resolve) | 36,781 | e758de63fadf024483769f6e6a9c475f2e808e49c16ec3af363d74b1bb8935a7 | timing compared by Charlie |
| pandoracut_episode_assembler.py at comparison time | 60,378 | 79ec055219e8eb453322141fb3cef243b48456b35518eec1990b7d5e2ae6e55d | reported (A5) |
| WIILT_EP9_V1_2_TOURNAMENT_AND_SIMULATOR_REPORT_A5_20261029.md | 7,095 | 81cb80d9ddb26d8371b972997dd653ba975530ff568c1f25bbb327bab87c6daf | re-hashed (Fable, Charlie); figures reported by A5 |
| WIILT_EP9_PANDORACUT_A5_1080P.mp4 | 393,500,758 | 1b548e3ff2b5715168099e35f2016d1b7bfcab0c585134348f007d9512eacb25 | reported (A5) |
| TS8 production annex | 4,090 | a5baa95c07d4de90ac8a9744ec5eac50657e3c7db0f91026221f326bcee0b312 | read by Charlie |
| TS8 v1.3.2 tournament JSON | 72,393 | a59a68f580a2a617802f8e67aaed88c67cebcf0e953d72dee50d8fd9ae151234 | read by Charlie |
| Recipe description text | 5,114 | 2f41946cefa398e08400bb39ce158dafbeff61f9bfb767a1a12e51b6a866db10 | read by Charlie (a description, not proof of emitted fields) |
| pandoracut_law_lock_verifier.py | 6,990 | 908fe50c77bd75b0da9e71f423e9b540ada64f867aeba1409f47eb695515ad57 | re-hashed (Fable, Charlie) |
| receipt_acceptance_gate.py | 6,727 | 0f69a3d09899dad6dda138e9ea3d2ece53124eb35147d1b96de8932d07df0976 | re-hashed (Fable, Charlie) |
| test_result.txt ("Ran 16 tests … OK") | 1,581 | 0dbc5d0fdc01ffa4d3f26bcf9646812caf9dd50820a1eed213666b25828b1bfd | re-hashed (Fable, Charlie) |
| blender_render_guard.py | 7,470 | d30b991000d603258ec4161115c052169beb5302de20e1e26762cb54a7fe8279 | author; re-hashed (Charlie) |
| TS8_v12_FIRSTGEN_CLEAN_1080P.mp4 (rebuild) | 311,413,764 | a647bdc63d723b21c57200b8b0e2eb7502d6e13684c4597da4aee9b57e519b7d | reported (Lotus) |
| TS8_v10_MUX_v7video_v10audio_14000k_20261026.mp4 | 754,463,169 | 0d2e53aa7800e1e6380f9ac8ad97a63e37839c074cc383e7b047acc8763197dd | re-hashed on the source machine (Fable) |
| ts8_v9_audio_roomtone_48k.wav (phantom-fill repair) | 121,704,006 | 7b5c5be3a8e8d595fb588f89521f19b346fc2f797d9ddd3c9cec2ff7c3228257 | reported (Vale) |
| GEMINI_LISTEN_RECEIPT_RUN1_TS8_V12_A4.json (Drive 1E-w1B2sGSxDVmC36UCvfor8tC9SyeKak) | 16,076 | 3a72a4cfad6d85a4fedb3539ecdfa8db104d3e253990fc3633e2d37300ae7dd9 | reported (A4); not re-hashed for RC2 (Lotus 09:41Z: A4's self-claimed receipt hashes need a re-pin) |
| GEMINI_LISTEN_RECEIPT_RUN1_TS8_V12_A4.md (Drive 12LoLqPPKT5Onv1SjOvAt85k6VSrTLgXV) | 12,443 | 2226f79b782c1e289a37e19f16abcc7d03ec2cea8e2effcc2ced2738003d033d | re-hashed as downloaded (Fable, RC2) |
| GEMINI_LISTEN_RECEIPT_RUN2_WIILT_EP9_A4.json | 6,994 | 558b6de496e27adcee989b76fd1c4d3b17cdd52a4c6be3eb4c0724f9686e9399 | reported (A4); not re-hashed for RC2 and not used as evidence |
| GEMINI_LISTEN_RECEIPT_RUN2_WIILT_EP9_A4.md (Drive 1v_6D82Rg0oaTMvAJXQI0fdYAUFV-G2K4) | 8,151 | fcf5afdf81f63cb427c918b574c5cc7078c8b7a1ac2b6faafa92fce0cf7e506c | re-hashed as downloaded (Fable, RC2) |
| TS8_v12_FIRSTGEN_CLEAN_1080P_ANNEX.json (Drive 1vB6mSe2li_I4tLAnUImXqDhlNvAYZtVi) | 4,090 | a5baa95c07d4de90ac8a9744ec5eac50657e3c7db0f91026221f326bcee0b312 | re-hashed as downloaded (Fable, RC2); same bytes as the "TS8 production annex" row |
| CHARLIE_PAPER_RELEASE_REVIEW.md (Drive 1EJWk_ivbhRQWUZP4X3Iv44wfvW75RVRG) | 6,068 | 52f90e56bc7ebe69273801c6d902217b599d132f7b4b7b5f929f21be735feeae | re-hashed as downloaded (Fable, RC2) |
| WIILT_EP9_DIALOGUE_PROVENANCE_GATE_FIXTURE_LILY_DOT_20261030 | Google Doc | no byte hash (a Doc, not a file) | reported (Lily Dot) |
| RL_PRODUCER_SCOREBOARD.json — **frozen snapshot** (seats updated 2026-10-30T04:49:31Z) | 10,308 | 11f8285f971aa7c463710696a5324cf0f53845e1c194117cc572049f450bb65c | re-hashed (Fable, Charlie). The live ledger keeps growing (10,986 B / 8ad44c4e…e08b at 06:4xZ); this paper cites the snapshot only |

## Appendix B — Contributions and idea origin

| Contributor | Contribution in this paper | Evidence |
|---|---|---|
| Manuel Avila | the producer's ear verdicts, quality targets, founder rulings; the verdict that anchors calibration | ledger sample 1 |
| Aifred (A4.1) | translated rulings into the laws in Section 2; directed the work | Court record |
| Lotus | instrument audits, calibration ledger, referee | ledger 7a16b783… |
| A5 (Luna) | standalone assembler, simulator, bridge tournament, law-lock verifier | Appendix A pins |
| A4 (Vester) | Resolve assembly and timing manifest; Topaz runs (operator-reported); Gemini native listen runs 1 and 2 | e758de63…; receipts 2226f79b… and fcf5afdf… (as downloaded) |
| Vale | phantom-fill root cause and v9 repair | Vol 7 receipt; 7b5c5be3… (reported) |
| Bravo | first ear_equation scorer, v0.2 to v0.2.2 | SF record |
| Charlie | independent timing comparison, Appendix A audit, adversarial acceptance gate | 0f69a3d0…; audit 06:17Z |
| Lily (signs as Lily Dot) | fact and continuity gates; raised the 091 dialogue-preservation question; Gate 1 review of v2 and the 091/113 script-to-timeline fixture | Court record; Vol 10 |
| Beni | generated the five TS8 Flow Music cues that feed the music-bed stage | MAN-58 receipt eede4d1e (prefix hashes only) |
| A6 | GPU operator work (not used as evidence here) | — |
| Delta | credited on the founder's byline; scorer contribution to be pinned from Delta's own receipt before it is described | pending |
| Lily YouTube 3 | credited on the founder's byline (joined 2026-10-30); a distinct seat from Lily; show-canon acceptance review of the breathing-room work | Vol 10 |
| Fable (A2) | wrote v1, v2, v2.1 RC1, RC2 and RC3 of this paper and the render guard | d30b9910… |

**Lead-author proposal, for the referee to ratify.** The idea of turning the producer's ear into numeric gates originates with Manuel Avila's own order (Court Brain Vol 7). The first running implementation was Bravo's scorer, and the calibration ledger is Lotus's. Fable drafted this paper but did not originate the idea, so Fable does not propose itself as lead.
