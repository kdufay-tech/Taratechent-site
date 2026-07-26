# TáraDome Musik

Public product site and interactive songwriting-studio prototype for the external **TEOS Musik** attachment.

## Included

- Responsive TáraDome Musik marketing experience.
- Interactive before-and-now lyric editor and genre-aware guidance controls.
- Local audio attachment and playback preview.
- Original, suggested, combined, and accepted lyric decisions.
- Browser-local draft persistence.
- TXT, Word-compatible document, and print-to-PDF delivery.
- Simulated secure TEOS launch and integration explanation.

## Run locally

```bash
python3 -m http.server 4173
```

Open `http://localhost:4173`.

## Production boundary

This repository represents the public Musik experience and external studio. TEOS remains the private ERP and system of record. Production integration should use single-use launch tickets, server-to-server exchange, scoped permissions, signed webhooks, and versioned APIs. Audio transcription, Claude-assisted refinement, document generation, storage, and email require the planned Railway, Supabase, Anthropic, and Resend services.
