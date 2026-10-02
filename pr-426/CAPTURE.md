# PR #426 captures

- **before_ai_summary.png** — live `https://staging.getpenny.ca` engagement Kelsey Moreau (Farah partner). Smashed one-line briefing: single `<h2>` containing literal `##` / `---`. Captured via Playwright after `document.fonts.ready` + Fraunces/IBM Plex checks (same gates as `e2e/helpers/screenshot.ts`).
- **after_ai_summary.png** — local `next dev` @ tip `bb6db54` (`WRANGLER_CONFIG=wrangler.e2e.jsonc`, firm brand **Penny CPA**). Same briefing facts with newlines preserved so `##` headings, `---` `<hr>`, lists, and paragraphs render. Captured with the same font/CSS gates.

Never Paradi. No hand-composed HTML fixture.
