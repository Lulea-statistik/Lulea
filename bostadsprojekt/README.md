# Bostadsprojekt i Luleå

Versionshanterade snapshots av privata/icke-kommunala källor för kommande, planerade, säljstartade och pågående nya bostadsprojekt inom Luleå kommun.

## Struktur

- `history.csv` – sammanhängande historik för alla snapshots. Kolumnen `Statusklass` skiljer mellan `Aktiv/verifierad` och `Bevakning`.
- `snapshots/YYYY-MM-DD_aktiva.csv` – verifierade aktiva/planerade projekt per körning.
- `snapshots/YYYY-MM-DD_bevakning.csv` – bevakningsfall med osäker, gammal, pausad eller motsägelsefull status.

## Tillgängliga snapshots

- 2026-09-25: 8 aktiva/verifierade + 5 bevakningsfall.
- 2026-10-02: 8 aktiva/verifierade + 5 bevakningsfall.

`history.csv` innehåller båda datumen och kan användas direkt som historikkälla i exempelvis Power BI.

Kommunala källor och kommunala bolag används inte som källa i denna sammanställning.
