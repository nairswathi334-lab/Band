# Band Medley Studio

A local-first, beginner-friendly medley arrangement planner for college bands.

## Features
- Competition brief built around instrument ability, vocal ability, musicianship, coordination, arrangement, originality, stage presence and overall performance.
- Performer roster with names, roles, style specialities, optional comfortable range, notes and 1–5 skill ratings.
- Song bank for source/version, language, BPM, tonic/key, raga/scale notes, desired song section, user-provided lyric cues and reference timestamps.
- Timestamped arrangement segments with lead/response assignments, exact lyric/section cues, instrument entry/exit notes and transitions.
- Blueprint export as TXT, project export as JSON, and timeline export as CSV.
- Browser-local save/load.
- Timing audit and rehearsal checklist.

## Run it
1. Upload `index.html` to a GitHub repository.
2. Open it locally in a browser, or enable GitHub Pages in repository Settings → Pages to publish the static app.
3. No build step, framework, API key, or server is required.

## Important limits
This is an arrangement planner, not an automatic audio-analysis engine. It does not independently identify a song's BPM, key/tonic, raga, exact lyric timestamps, or whether two melodies can safely overlap. Treat those fields as unverified until checked against an authorised recording, notation, or a qualified musician. Add the song-specific lyric cues and exact timestamps yourself; the app uses those to create a detailed rehearsal blueprint.

For copyrighted songs, this app does not ship with complete lyrics. Enter your own short rehearsal cues or section labels (for example, “Pallavi, first line through final repeat”) and refer to authorised lyric sources and recordings. Confirm any performance/licensing requirements with the event organiser.

## Suggested next development step
Add audio-file import and signal-analysis modules for BPM and section-change estimates, then add musician-reviewed tonic/melody compatibility checks. Accurate raga identification and lyric alignment should remain verified outputs rather than guesses.
