# Projektname: SparzieleTracker

## Ausgangslage
Viele Menschen haben Schwierigkeiten, ihre finanziellen Ziele im Blick zu behalten. Oft fehlt eine einfache und visuelle Möglichkeit, Sparziele zu definieren, regelmässig Fortschritte zu dokumentieren und motiviert zu bleiben. 

## Projektidee / Funktion
Die Anwendung soll Nutzer:innen helfen, persönliche Sparziele zu setzen, Fortschritte zu dokumentieren und den aktuellen Stand visuell darzustellen. Die App motiviert durch eine klare Übersicht und kleine Erinnerungen zum Weitersparen.

## Ansichten (UI)
- Startseite mit Übersicht aller Sparziele
- Ziel-Detailseite mit Fortschrittsanzeige (z. B. Balken oder Kreisdiagramm)
- Neues Sparziel erstellen
- Sparbetrag hinzufügen
- Übersicht vergangener Einzahlungen
- Einstellungen (Währung, Erinnerungen)

## Datenverarbeitung
- Sparziel (Name, Zielbetrag, Startdatum, Beschreibung)
- Einzahlungen (Datum, Betrag)
- Berechnungen: Fortschritt in %, verbleibender Betrag, durchschnittlicher Sparbetrag pro Woche/Monat

## Nutzerfunktionen
- Neue Sparziele erstellen, bearbeiten und löschen
- Einzahlungen hinzufügen
- Fortschritt anzeigen lassen (visuell und in Zahlen)
- Ziele als "erreicht" markieren
- Erinnerungen setzen (optional)

## Quellen
Die App verwendet ausschliesslich lokale Daten, gespeichert in einer SQLite-Datenbank über SQLAlchemy. 
