# Band Medley Studio

A beginner-friendly, local-first medley planning app for college bands.

## New in this version
- A searchable starter catalogue of songs in Malayalam, Tamil, Kannada, Hindi, Telugu and English.
- Add catalogue songs to your editable Song Bank with one tap.
- Describe the kind of medley you want in everyday language; the app creates a beginner-friendly starter flow with approximate timing and transition/rehearsal cues.
- Build a copyable AI prompt using your song list, performers, instruments, competition duration and desired mood.
- Import song titles from TXT/CSV/Markdown files, text-based PDFs, or scan a photo/screenshot with browser OCR.
- Separate instrument inventory with common instruments and custom equipment notes.
- Existing performer roster, timestamped arrangement, timeline audit, rehearsal checklist, TXT/JSON/CSV exports and browser-local save/load remain available.

## Run or publish
1. Upload `index.html` and `README.md` to the root of a GitHub repository.
2. To publish it, open repository **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
3. Open the GitHub Pages URL shown on the Pages screen.

The main planner works as a static page. Image OCR and PDF reading load browser libraries from a CDN and therefore require internet access. If the app is opened directly from a phone's file manager, some browser features may be restricted; GitHub Pages is the recommended way to use it.

## AI and music accuracy
The built-in planner is a structured starter assistant, not a live AI model and not an audio-analysis engine. The song catalogue is a curated starter list, not a real-time trending chart. The copyable AI prompt can be pasted into an AI assistant for a more detailed blueprint. For in-app live AI responses, deploy a secure backend that accepts `POST` JSON such as `{ "prompt": "..." }` and returns JSON with a `text` or `plan` field; enter that backend URL in the app. **Do not put a private AI API key in this public HTML file.**

The app does not independently verify BPM, key/tonic, raga, tala, exact lyric timestamps, current popularity, or whether two melodies can safely overlap. Do not treat approximate section timings as exact audio timestamps. Check actual recordings, singer comfort, melody/tonic, rhythm, and transitions in rehearsal; if two melodies clash, use a short instrumental/percussion bridge instead of forcing an overlap.

For copyrighted songs, the app does not ship with complete lyrics. Use short cues or section labels and refer to authorised recordings/lyrics. Confirm performance/licensing requirements with the event organiser.
