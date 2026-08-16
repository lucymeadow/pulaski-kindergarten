# Will's Kindergarten — Pulaski 2026–27

A single-page tracker for the start of kindergarten: to-dos, open questions, the daily routine, money, and every day off.

**Live site:** https://lucymeadow.github.io/pulaski-kindergarten/

## Updating it

Everything lives in `index.html` — no build step, no dependencies. Task state is in the `TASKS` array near the bottom; flip `done:false` to `done:true` and the checkbox, the per-group count, and the progress bar all update on their own. The `QA` array works the same way with `s:"open"` / `s:"answered"`.

## What's deliberately not here

This repo is public, so the source material is kept out of it: the original school emails, the Apollo and ChicagoSMA confirmation screenshots, and the staff organization spreadsheet. Those contain both parents' email addresses, payment details, and the names of every staff member at the school. The site is built from them but doesn't republish them.

Also omitted from the site: exact door and room details are kept minimal, staff email addresses are obfuscated, and the ChicagoSMA allergy form link is left out.

## Sources

- Principal Racasi's summer update (18 Jun 2026) and back-to-school letter (11 Aug 2026)
- ChicagoSMA Session 1 and Hip Hop Camp registration confirmations
- Apollo before/after care confirmation
- Kindergarten Supply List 2026-2027
- Pulaski SY 26/27 Staff Organization Chart — verified against the live version
- Pulaski 2026/2027 6-Day Essential Subjects Class Schedule
- Official CPS 2026–27 Family Calendar

Anything flagged *verify* on the site is either missing from those sources or contradicted between two of them.
