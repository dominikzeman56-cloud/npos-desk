---
name: npos-desk
description: >
  Rozhodovací session vedle npos-v2. Čte npos a vault, zapisuje jen do npos-desk
  (session log, overlay). Use when the user says npos-desk, session log, další
  akce v session, bass_type overlay, or /npos-desk. Nikdy nezapisuje do npos-v2.
---

# npos-desk

Pravidla a stop-list jsou v `docs/DIRECTION.md` tohohle repa. Skills, které brát a které ne, jsou v `docs/SKILLS.md`. Sem se nekopírují.

## Session

1. Zeptej se na fázi, jen když ji uživatel neřekl. Fáze hledej v `D:\Dev\Projects\npos-v2\knowledge\guides\next-step.json` a vyber jednu další akci.
2. Po práci zapiš `sessions/YYYY-MM-DD-<track_id>.json`. Povinná pole ber z `D:\Dev\Projects\npos-v2\core\session.schema.json`.
3. `track_id` je rozdělaný track, ne referenční id z korpusu.

## Overlay

`bass_type` doplň jen ze stemů nebo z A/B v Serumu. Claim z plného mixu zapiš do `why` a typ nech `null`. Vzor je `overlays/tracks.json`.

## Zákaz

Žádný zápis pod `D:\Dev\Projects\npos-v2`. Žádné kopírování `_sources/`, presetů ani přepisů. Žádný nový nástroj, dokud na větu nestačí výstup, který v npos už je.
