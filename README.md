# Swarnim Dwar — Chandel Family Invitation

React + Vite invitation site with Tailwind theme tokens, Framer Motion transitions, responsive sections, RSVP WhatsApp deeplink, and editable event config.

## Run locally
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
npm run preview
```

## Update details
Edit `src/config/eventData.js`. Fill the timing, venue address, map URL/embed URL, host phone and WhatsApp number. WhatsApp should be entered as country code + number (digits only recommended), without `+`.

Optional audio: place lightweight audio files at public paths and set `backgroundTrackUrl` / `bellSoundUrl` in eventData.js (for example `/audio/bg-flute.mp3`). Background audio starts muted and only plays after the guest explicitly taps the audio toggle.

## Notes
- Countdown is set to the Grah Pravesh muhurat target of 10 March 2026 at 09:00 IST and automatically transitions through event/live/gratitude states.
- Address, map, phone and WhatsApp fields are intentionally placeholders. No address or contact information has been invented.
- Custom motifs are inline SVG/CSS. `public/og-preview.svg` is a vector OpenGraph placeholder preview. Replace with a 1200×630 branded raster image if preferred.
