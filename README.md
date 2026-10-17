# Health Hub
Save path: C:/MarvelApps/healthhub/README.md

Live (once pushed): https://smarvel1963-ops.github.io/healthhub/ - app #8 of the Marvel Corp Hub family (Scott 2026-10-17,
plan: C:/MarvelDesktop/docs/HEALTH_HUB_PLAN_FROM_OUTSIDE_CHAT_2026-10-17.md).

This repo is Health Hub's OWN shell: index.html, manifest.json, icons and sw.js. The app itself is the shared Hub
engine in the Day Hub repo run with window.DH_MODE = "health" plus health.js.

- Own data on the phone (healthhub.v1). Record photos live in IndexedDB (healthhub.vault) and never go in the backup.
- v1 (1.53): Wellness Orbit home + Health Score, Medications (Taken / Skipped, pills left, refill countdown, label scan
  with a review form), Appointments (questions, what to bring, notes, visit summary), Vitals (BP, glucose, weight, heart
  rate, oxygen - gauges, trends, general ranges), Movement & gym, Sleep, Water, Daily check-in, Records vault,
  Emergency card.
- Friend step challenges = the CHALLENGES switch in ../dayhub/features.js, OFF (needs a relay task "challenge").
- Never medical advice and never dosing: ranges are general published guidelines, labelled as such.
- Icons from the Hub series concept logo (../dayhub/brand/hub_series_20_logos_2026-10-11/health_hub_logo.png).
- Tests + release steps: the Day Hub repo (python tests/run_tests.py).
