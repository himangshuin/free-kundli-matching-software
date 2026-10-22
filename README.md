# বিবাহ যোৰা বিচাৰ · Marriage Matchmaking
Static app (GitHub Pages ready): Ashtakoota 36-guna match, dosha checks (Nadi, Bhakoot, Gana, Manglik, Rajju, Vedha, Mahendra) and a written prediction.
Assamese (default) / English. Moon and Mars positions come from `data/ephemeris.csv` (1930-2061, Lahiri). Saved people stay in the browser (localStorage).
Places: `data/places.csv` (name,lat,lon,tz). Vashya uses the onlinejyotish bride x groom table; Gana uses a bride x groom table (edit `VT` / `GT` in index.html to change).

## v2 additions (from the compatibility guide)
Manglik from Lagna, Moon and Venus (weights 1/2/3) with the classical cancellations (sign-by-house table, Leo/Aquarius, Mars with Jupiter or Moon, Jupiter/Venus in Lagna, both partners Manglik); Nadi, Gana and Rajju exceptions; Stree Deergha; same star & pada rule; classical Rasi-kuta reading; Vedha list corrected (Chitra gives/gets none); "good" band starts at 26.
- v3: D1 birth charts for boy and girl (East/North/South Indian) with graha table, from all nine ephemeris bodies.
- v4: D9 navamsa toggle, copy/WhatsApp summary, export/import of saved people, edit button, auto-match on selection.
- v5: running Vimshottari dasha (MD/AD/next MD), 7th-house indicators per chart, traditional remedies for present doshas, ages.
