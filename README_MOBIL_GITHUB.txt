ADR Gods - GitHub mobilvennlig pakke

Denne pakken er laget for opplasting fra mobil til GitHub uten undermapper.
Alle kildefiler ligger flatt i repo-rota.

Slik bruker du den:
1. Last opp ALLE filene i denne pakken til repo-rota på GitHub.
2. Opprett deretter filen .github/workflows/build.yml
3. Lim inn innholdet fra build.yml-filen i denne pakken.
4. Commit changes.

Bygg:
- GitHub Actions kjører reconstruct_project.py
- Scriptet lager korrekt Android-mappestruktur automatisk
- APK bygges deretter i skyen

Når builden er ferdig:
Actions -> Build ADR Gods APK -> Artifacts -> ADR-Gods-APK
