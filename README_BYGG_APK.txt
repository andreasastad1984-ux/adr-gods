ADR Gods - Android Studio prosjekt med scanner

Dette prosjektet inneholder:
- ADR Gods som appnavn
- lokal ADR-kalkulator i WebView
- knapp for kamerascanning
- OCR-lesing av UN-nummer (ser etter UN1234 eller 1234)
- favoritter og lokal lagring via HTML-appen

Slik bygger du APK:
1. Pakk ut zip-filen på PC.
2. Åpne mappen i Android Studio.
3. Vent til Gradle-sync er ferdig.
4. Velg Build > Build APK(s).
5. Installer APK-en på Android-telefonen.

Viktige filer:
- app/src/main/assets/www/index.html
- app/src/main/java/no/adrgods/app/MainActivity.kt
- app/src/main/java/no/adrgods/app/ScanActivity.kt
