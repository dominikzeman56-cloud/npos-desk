# Vigil — kostra proti RipX stemům

2026-10-17. Soubory `Ekwols - The Vigil Abyss_{Bass,Drums,Other}.wav`, 339,3 s. npos beze změny. Starší krátké klipy v `30_Stems` zůstaly na disku, do repa nejdou.

Kostra MIDI (`MIDI_ekwols`, 8 taktů, psaná na 172 kvůli Dirtse) se neměnila. Špičky 2,90 / 5,80 / 11,60 Hz sedí o chlup líp na 174. To je asi 1 %. Není důvod přepisovat noty.

Obálka je `analyze_track` pásmo 60–300 Hz. Nástroj hlásí jen špičky nad polovinou primáru. U 67–108 s se vítěz otočí, když okno zkrátíš o 10 ms (0,73 versus 2,89, poměr 0,99). Proto jsou tu poměry, ne jeden štítek.

| Okno | Co v basu vede | Proti kostře |
|---|---|---|
| 67,1–108,2 s, nejdelší hlasitý úsek | 0,73 a 2,89 skoro stejně, osmina 0,76, šestnáctina 0,73 | sub 0,72 a reese 2,87 jsou v té hromadě, nevlastní ji |
| 133,4–153,9 s | osmina 5,80, šestnáctina 0,65, čtvrť 0,51 | sedí na roll a cluster (medián osmina) |
| 177,5–209,1 s | 0,70, čtvrť chybí, centroid 357 Hz | starý klip měl taky 0,7 Hz. Nový stem to neposunul |
| 216–224 s, vault | 2,9 Hz v basu není. Drums 11,62 Hz = šestnáctina | full mix 11,67 Hz byl bicí. Sekce je breakdown 209–228 |
| 23,1–51,5 s | 1,44 a 0,53 | pomalejší než reese fráze |

Rozestup špiček 350–900 Hz v okně 216–224 je 2,7 Hz, 88 špiček. Stem je pořád celá basa, ne izolovaná držená nota. `reese` jako typ se nezapisuje.

Verdikt: osminová půlka kostry (B) má oporu v obálce. Čtvrťová věta z vaultu mířila na špatných 8 sekund. V dlouhém dropu jsou takt, čtvrť, osmina i šestnáctina stejně nahlas. `bass_type` zůstává prázdný.
