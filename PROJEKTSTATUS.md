# 📋 TrainerPro – Projektstatus

> Hier siehst du den aktuellen Entwicklungsstand nach Phase.
> Dieses Dokument wird mit jeder abgeschlossenen Phase aktualisiert.

---

## 🔄 Gesamtfortschritt

| Phase | Bereich | Woche | Status |
|-------|---------|-------|--------|
| **1** | Fundament, Verein, Mannschaft | 1–2 | ⬜ Geplant |
| **2** | Kader, Terminkalender | 3–4 | ⬜ Geplant |
| **3** | Aufstellung, Matchday-Protokoll | 5–6 | ⬜ Geplant |
| **4** | Statistiken, Auswertungen | 7 | ⬜ Geplant |
| **5** | Übungsbibliothek, Rechte | 8 | ⬜ Geplant |
| **6** | Scouting | 9 | ⬜ Geplant |
| **7** | Dashboard, Mobile Design | 10 | ⬜ Geplant |
| **8** | Deployment, Go-Live | 11–12 | ⬜ Geplant |

**Legende:** ✅ Fertig · 🟡 In Arbeit · ⬜ Noch nicht begonnen

---

## 📌 Was wird gerade gebaut?

> Dieser Abschnitt wird laufend aktualisiert.

Aktuell: **Phase 1 – Grundgerüst**

Das technische Fundament der App wird aufgebaut:
- Datenbankstruktur für Vereine, Mannschaften, Spieler und alle weiteren Bereiche
- Anmeldung & Registrierung
- Verein erstellen und per Code beitreten
- Mannschaft erstellen und per Code beitreten

---

## ✅ Phase 1 – Grundgerüst, Verein & Mannschaft

*Ziel: Die App startet, man kann sich registrieren, einen Verein gründen und eine Mannschaft anlegen.*

- [ ] App lässt sich aufrufen und zeigt eine Startseite
- [ ] Registrierung und Anmeldung funktionieren
- [ ] Verein anlegen (Ersteller wird automatisch Administrator)
- [ ] Einem Verein per 6-stelligem Code beitreten
- [ ] Administrator eines Vereins ernennen
- [ ] Mitglieder aus dem Verein entfernen
- [ ] Mannschaft innerhalb eines Vereins anlegen
- [ ] Einer Mannschaft per Code beitreten
- [ ] Mannschafts-Einstellungen bearbeiten (z. B. Standard-Spielzeit)

---

## ✅ Phase 2 – Kader & Terminkalender

*Ziel: Spieler im System erfassen und Termine sowie Termin-Serien anlegen. Spielerstatus und Anweseheitsliste anzeigen.*

- [ ] Spieler anlegen (Name, Position, Trikotnummer, Geburtsdatum)
- [ ] Spielerstatus verwalten: Verfügbar / Verletzt / Gesperrt
- [ ] Spieler bearbeiten und aus dem Kader entfernen
- [ ] Termine anlegen: Training, Spiel, Testspiel, Turnier, Aktivität
- [ ] Wiederkehrende Termine als Serie anlegen (z. B. jeden Dienstag)
- [ ] Einzelnen Termin einer Serie separat bearbeiten
- [ ] Alle folgenden Termine einer Serie auf einmal anpassen
- [ ] Anwesenheitsliste pro Termin erfassen (anwesend / fehlend / entschuldigt)

---

## ✅ Phase 3 – Aufstellung & Spielberichte

*Ziel: Aufstellungen planen und Spielergebnisse sowie Spielereignisse dokumentieren.*

- [ ] Formationen speichern (4-3-3, 4-2-3-1, 4-4-2, …)
- [ ] Spieler per Drag & Drop auf dem Spielfeld positionieren
- [ ] Spieler als Startelf, Bank oder nicht nominiert markieren
- [ ] Aufstellung als Vorlage speichern und wiederverwenden
- [ ] Spielbericht anlegen: Ergebnis, Tore, Karten, Auswechslungen
- [ ] Tore, Karten und Auswechslungen minutengenau erfassen
- [ ] Turnierbericht: Einzelspiele mit Gegnern, Phasen und Ergebnissen
- [ ] Endplatzierung und Finalrundeneinzug beim Turnier festhalten

---

## ✅ Phase 4 – Statistiken & Auswertungen

*Ziel: Aus den Spielberichten werden automatisch nützliche Auswertungen.*

- [ ] **Leistungstracker:** Tore und Karten je Spieler in der Saison
- [ ] Torschützenliste und Kartensünder-Liste (sortierbar)
- [ ] **Spielzeittracker:** Wie viele Minuten hat jeder Spieler gespielt?
- [ ] Auslastung in Prozent berechnen
- [ ] Turnier-Spielzeit berücksichtigen
- [ ] **Saisonstatistik:** Siege, Niederlagen, Unentschieden, Punkte, Tordifferenz
- [ ] Heim- und Auswärtsstatistik getrennt anzeigen
- [ ] Turnierergebnisse: Platzierungen, Finalrundeneinzüge
- [ ] **Konditionstest:** Lauf- und Ausdauertests eintragen
- [ ] Entwicklungskurve je Spieler als Diagramm anzeigen
- [ ] Mannschaftsdurchschnitt und Bestleistung hervorheben
- [ ] **Jahrgangsübersicht:** Altersverteilung und nächste Geburtstage

---

## ✅ Phase 5 – Übungsbibliothek & Zugriffsrechte

*Ziel: Trainingsübungen für den ganzen Verein sammeln und Rechte klar regeln.*

- [ ] Trainingsübungen anlegen (mit Kategorie, Dauer, Spieleranzahl, Material)
- [ ] Übungen sind für alle Trainer des Vereins sichtbar
- [ ] Eigene Übungen bearbeiten
- [ ] Löschanfrage stellen (Trainer) – Administrator entscheidet
- [ ] Übungen endgültig löschen (nur Administrator)
- [ ] Zugriffsrechte: wer darf was sehen, bearbeiten, löschen

---

## ✅ Phase 6 – Scouting

*Ziel: Interessante Spieler beobachten und den Prozess bis zur Entscheidung dokumentieren.*

- [ ] Gesichteten Spieler erfassen (Name, Verein, Position, Kontakt)
- [ ] Status setzen: beobachtet → interessant → kontaktiert → Probetraining
- [ ] Probetrainings mit Datum und Notizen eintragen
- [ ] Anzahl der Probetrainings automatisch zählen
- [ ] Entscheidung treffen: Zusage / Absage / Selbst abgesagt (mit Begründung)
- [ ] Scout für den Vereinsadministrator freigeben
- [ ] Administrator sieht alle freigegebenen Scouts vereinsweit

---

## ✅ Phase 7 – Dashboard & mobiles Design

*Ziel: Übersichtliche Startseite und angenehme Nutzung auf dem Handy.*

- [ ] Dashboard mit den wichtigsten Informationen auf einen Blick
- [ ] Nächste Termine anzeigen
- [ ] Aktuelle Verletzte und Gesperrte auf dem Dashboard
- [ ] Nächste Geburtstage anzeigen
- [ ] Letzte Anwesenheitsquote sichtbar
- [ ] App funktioniert gut auf Smartphones (Spielfeldrand-Nutzung)
- [ ] Klare Navigation zwischen Verein, Mannschaft und Funktionen
- [ ] Verständliche Fehlermeldungen und Erfolgs-Hinweise

---

## 🚀 Phase 8 – Veröffentlichung

*Ziel: Die App ist online erreichbar unter einer eigenen Adresse.*

- [ ] Server mieten und einrichten
- [ ] Eigene Web-Adresse (Domain) registrieren
- [ ] App auf dem Server veröffentlichen
- [ ] Automatische Updates bei neuen Versionen
- [ ] Tägliche Datensicherung einrichten
- [ ] App öffentlich erreichbar und stabil

---

## ✍️ Zuletzt aktualisiert

**Mai 2026** – Projekt gestartet, Phase 1 geplant

---

*TrainerPro · Öffentliches Projekt-Repository · Status wird regelmäßig aktualisiert*
