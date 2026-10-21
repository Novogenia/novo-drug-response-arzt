# NOVO Drug Response – Arztversion

Software für Ärztinnen und Ärzte zum Pharmakogenetik-Test von Novogenia: Kundenübersicht, Import der
Ergebnisdatei (Formel-Output in Textform), Einstellungen je Kunde, Löschen; Standard- und Expertenmodus.
Enthalten ist ein anonymisierter Beispielkunde.

**Zweckbestimmung:** zeigt und verwaltet die Ergebnisdateien, die das Labor der Novogenia je Kunde erstellt.
Bewertungen und Begründungen stehen unverändert wie in der Datei, Leitlinien- und Literaturtexte (CPIC, DPWG,
FDA, ClinPGx) im Wortlaut; deutsche Übersetzungen sind nicht validiert, maßgeblich ist die englische Fassung.
Die Software berechnet, interpretiert oder verändert keine Ergebnisse und gibt keine eigenen Empfehlungen –
kein Medizinprodukt. Diagnose, Therapie und Verordnung verantwortet die behandelnde Ärztin bzw. der Arzt.

**Daten:** importierte Dateien bleiben im Browser des Nutzers (IndexedDB); die Seite sendet nichts.

**Ansehen:** https://novogenia.github.io/novo-drug-response-arzt/

Dieses Repository enthält nur die gebaute App (`index.html`, `data/clinpgx_alle.json`). Herkunft und Lizenz der
Daten: [LICENSE-DATA.md](LICENSE-DATA.md) (ClinPGx/PharmGKB, CPIC, PharmCAT unter CC BY-SA 4.0).
Stand: 21.10.2026. Prototyp.
