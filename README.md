# World Cup Alpint Wyllerløypa 2028

Denne pakken inneholder en enkel statisk GitHub Pages-side for å navigere mellom:

- Business case
- Prosjektplan
- Produktbeskrivelser og produktnedbrytningsstruktur
- DOCX-nedlastinger for begge dokumenter
- Excel-filer for KPI, governance, seniorroller, prosjektstyre, prosjektlogg og faseplaner
- PowerPoint-mal for ukentlig team-scorekort

## Struktur

```text
docs/
  index.html
  styles.css
  assets/
    logo.png
  documents/
    business-case.html
    business-case.docx
    prosjektplan.html
    prosjektplan.docx
    produktbeskrivelser.html
    kpi-matrise.xlsx
    governance-matrise.xlsx
    seniorbrukere-seniorleverandorer.xlsx
    prosjektstyre.xlsx
    prosjektlogg.xlsx
    faseplaner.xlsx
    ukentlig-team-scorekort.pptx
```

## Publisering på GitHub Pages

1. Opprett et nytt repository på GitHub.
2. Last opp hele innholdet i denne mappen.
3. Gå til `Settings` -> `Pages`.
4. Velg `Deploy from a branch`.
5. Velg branch `main` og folder `/docs`.
6. Lagre. GitHub viser en publiseringslenke når siden er klar.

## Lokal bruk

Åpne `docs/index.html` direkte i nettleseren for å teste navigasjonen lokalt.
