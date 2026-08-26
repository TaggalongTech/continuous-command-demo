# Continuous Command — SuiteWorld demo site

Live at **https://ttg2020.github.io/continuous-command-demo/**

A Continuous-branded demo website for SuiteWorld: Continuous Command as the high-volume usage
rating engine on the NetSuite platform. The landing page is the marketing shell; **See it live**
opens the Live Rating Console (streaming rated events, throughput counters, ingest pipeline, and
the three demo accounts: Crestline Data, Meridian Cloud, Bluefin Robotics — matching the
NetSuite demo data).

Everything is fictional and fully self-contained in `index.html` (no external requests).

## Presenter keys (console)

- `Space` — pause / resume (freeze mid-pitch)
- `S` — surge: ~10x volume spike for ~8 seconds
- `R` — re-seed the day counters

## Updating

Canonical source lives in the armdemo workspace at `marketing/website/src/` (`site-src.html` +
`build.py`). Rebuild there, copy the built file here as `index.html`, commit, push.
