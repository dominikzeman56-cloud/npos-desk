# Směr

npos-v2 je archiv a měřicí stroj. Rozhodnutí vznikají tady. Cesta ke čtení: `D:\Dev\Projects\npos-v2`. Zápis tam je zakázaný, včetně dokumentace, dat a větve.

## Osa

1. **Session.** Před prací jedna fáze z `knowledge/guides/next-step.json` (jen číst) a jedna další akce. Po práci jeden soubor v `sessions/` podle `core/session.schema.json`. Pět logů, z toho aspoň jeden změnil, co se v setu udělalo. Když dva týdny nepřibude log, nové nástroje se nestaví.
2. **Spory, které už mají zdroj.** Fronta je `knowledge/principles/candidates.md` v npos (C8 rytmus not versus LFO, C2 sub mimo bass bus, C10 warp oscilátorem s hlasitostí 0). Výstup je věta se zdrojem a jistotou, zapsaná sem. Nový skript až když stávající výstup npos na tu větu nestačí.
3. **Seed bench** jen když session log má `blocked` na basovém patchi. Strop 20–30 vlastních presetů, verdikt uchem, výstup lokálně mimo obě repa. Žádný model nad feature vektory.
4. **Lint setu** až z faktu, který se opakoval v analýze a v session. Čtení, žádný zápis do `.als`.

## Stop

Žádné další indexování packů, žádné UI, žádná neuronka, žádný druhý most do Live, žádná stem-separation pipeline, žádné generování `.als`, žádné oživení `neuroman/`, žádný generátor tracků. Call/response a „co dělají producenti“ se nepíšou, dokud to není změřené.

`bass_type` se doplní jen z izolovaného pásma nebo z A/B v Serumu. Recept v rozboru, který staví na modulaci z plného mixu, typ nevyplňuje. Prázdné pole zůstane prázdné.

## Krok, který už proběhl

Čtyři tracky v korpusu npos mají `bass_type` prázdný. Overlay v tomhle repu to nechává prázdné a říká proč: [`overlays/tracks.json`](../overlays/tracks.json). Vaultové rekonstrukce *Don't Play*, *Been About This* a *Restless* pořád popisují LFO/AM z plného mixu. Kánon (`40 Mix a master`, řádek 16) tu 1/16 modulaci označil za artefakt. Doplnit z toho `growl` nebo `reese` by bylo opačné, než k čemu měření došlo.

## C8 (2026-10-17)

Tabulka: [`experiments/c8.md`](../experiments/c8.md). Nepovyšovat. Izolovaný mid bass Don't Play má obálku na čtvrťové (2,86 Hz), pYIN MIDI téhož stemu medián na osmině. Sub má obálku jednou za takt a přepis na šestnáctinách. Ekwols Vigil na disku není.

## Další práce

A/B na C10 je poslech v Serumu, ne commit do npos. Porovnání MIDI basy a audio chopu po taktech v jednom resamplovaném projektu je jiný experiment (session 2026-10-17), ne opakování C8.
