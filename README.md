# Stundentabelle

Zeitaufzeichnung pro Kunde – im Browser und am Handy.

- **App:** https://calliari6.github.io/stundentabelle/
- **Daten:** liegen im privaten Repo `stundentabelle-daten` (`meta.json` für Kunden/Einstellungen, `jahre/JJJJ.json` für die Stunden). Jede Änderung ist dort als Version nachvollziehbar.
- **Zugang:** Beim ersten Öffnen auf einem Gerät einen GitHub-Schlüssel (Fine-grained token, nur für `stundentabelle-daten`, *Contents: Read and write*) einfügen. Der Schlüssel bleibt nur auf diesem Gerät.

Funktionen: Kunden-Umschalter mit Stundensatz je Kunde, Ansicht „Alle Kunden“, Kommen/Gehen-Knopf, Beträge ausblendbar, PDF-Stundennachweis, Excel-Export im Format der Vorlage, Excel-Import, Backup. Funktioniert auch offline – Änderungen werden übertragen, sobald wieder Netz da ist.

Am Handy: Seite öffnen → „Zum Home-Bildschirm hinzufügen“.
