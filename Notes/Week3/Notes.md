# Notes
## GD
- Ist zustand vom GD fehlt (Cumulus)
  - Todo: Mit thore ist zustand sammeln
    - Architektur neu - ist 
- Datengröße
  - 400k Daten
    - Primär Bilder vom GD (PNGs, JPGs)
    - PDFs mit Bibliografischen Infos (Fachbeiträge etc)
    - Mehrere Terrabyte
- CSW Schnittstelle führt zu Geoportal -> Open NRW
- Todo: Deployment Diagrammm 
  - Wo wirds gehostet? 
  - Evtl in Deutsche Verwaltungscloud
  - Evtl Kubernetes
  - Amazon S3 (Simple Storage nicht unbedingt Amazon)
- Grund zum Wechseln
  - Cumulus gibt es in der Form nicht mehr (nur in Cloud, darf GD nicht)
  - Open data gesetz NRW (EGvG 16a NRW) -> Veröffentlichung notwendig
  - GEOIDG -> Veröffentlichung notwendig 
  - Inspire Regelugn -> Veröffentlichung notwendig
  - ->Alle daten müssen veröfentlicht werden 
  
- Zwischenpräsentation nach Abschluss des GD Projekts

## DZ Gefahr
- Viel Open Source
  - Öffentliche stellen wollen open source
  - Ergebnis: Open Pioneer
    - Developer Friendly
    - GD Dateninfrastruktur für Open Source
    - Langzeitpflege/Nachhaltigkeit ist das Ziel (z.b. 50 Jahre für spezielle projekte)
- Verschiedensteste 3 Librarys für Open Source 3d mit Open Layers
  - Verschiedene EPSGs. Wie in 3d Umrechnen? Oder ETRS89 in Cäsium lernen. 
- Riesige Datenmengen (16TB)
  - Performance Notwendig!