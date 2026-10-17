# Session

Jeden soubor na session, jméno `YYYY-MM-DD-<track_id>.json`. Tvar bere z `D:\Dev\Projects\npos-v2\core\session.schema.json` (jen číst). Povinné: `date`, `track_id`, `goal`. Když to jde, i `done`, `blocked`, `learned`, `next`.

`track_id` je to, co se právě píše, ne id referenčního tracku v korpusu. Log nepatří do `neuroman/data/sessions`.
