# Schéma cz-ndic_d2-itp-table-v2.1

DATEX II 3.4, vstupní soubor `DATEXII_3_D2Payload.xsd`. Převzato z dodávky dat GN 2026.06 (5. 8. 2026), se kterou je produkce validní.

* Schéma vzniklo ve webtoolu DATEX II 3.4 z `sel/cz-ndic_d2-itp-table.sel` (verze 2.0).
* Proti vygenerovanému schématu 2.0 je v `DATEXII_3_Common.xsd` ručně doplněna hodnota `heavyVehicle` ve výčtu `VehicleTypeEnum`; výběr ji zatím neobsahuje. **K řešení:** přidat hodnotu do výběru a schéma vygenerovat znovu (ruční úpravy vygenerovaných schémat se nedoporučují).
