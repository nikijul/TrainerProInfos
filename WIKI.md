# 📖 TrainerPro – Funktions-Wiki

> Hier werden alle Funktionen der App ausführlich erklärt –  
> verständlich für jeden, auch ohne technisches Vorwissen.

---

## Inhaltsverzeichnis

1. [Wie funktioniert TrainerPro?](#1-wie-funktioniert-trainerpro)
2. [Rollen: Wer darf was?](#2-rollen-wer-darf-was)
3. [Verein & Mannschaft](#3-verein--mannschaft)
4. [Kader – Spieler verwalten](#4-kader--spieler-verwalten)
5. [Terminkalender](#5-terminkalender)
6. [Anwesenheitsliste](#6-anwesenheitsliste)
7. [Aufstellungsplaner](#7-aufstellungsplaner)
8. [Spielberichte & Matchday-Protokoll](#8-spielberichte--matchday-protokoll)
9. [Statistiken](#9-statistiken)
10. [Konditionstest-Tracker](#10-konditionstest-tracker)
11. [Übungsbibliothek](#11-übungsbibliothek)
12. [Scouting](#12-scouting)
13. [Dashboard](#13-dashboard)

---

## 1. Wie funktioniert TrainerPro?

TrainerPro ist eine **Web-App** – das bedeutet, sie läuft im Browser (wie eine Website), muss aber nicht heruntergeladen werden. Sie funktioniert auf dem Computer, Tablet und Smartphone.

Der Grundaufbau ist einfach:

```
Dein Account
└── Verein (z. B. „FC Beispielstadt")
    ├── Mannschaft A (z. B. „U13")
    │   ├── Kader (Spieler)
    │   ├── Termine
    │   ├── Aufstellung
    │   ├── Spielberichte
    │   ├── Statistiken
    │   └── Scouting
    └── Mannschaft B (z. B. „U15")
        └── ...
```

Ein Nutzer kann Mitglied in mehreren Vereinen sein und dort unterschiedliche Rollen haben.

**Erreichbar unter:** *tba*

---

## 2. Rollen: Wer darf was?

### Vereinsadministrator

Der erste Nutzer, der einen Verein anlegt, wird automatisch zum Administrator. Er kann:

- Den Verein verwalten (Name, Logo, Beschreibung)
- Andere Trainer zum Administrator machen
- Mitglieder aus dem Verein entfernen
- Den Einladungscode des Vereins sehen (6-stellig)
- Alle Mannschaften des Vereins einsehen
- Übungen aller Trainer bearbeiten und löschen
- Löschanfragen für Übungen sehen und entscheiden
- Alle freigegebenen Scouting-Einträge vereinsweit sehen
- Die Altersverteilung aller Spieler im Verein sehen

### Trainer

Trainer kümmern sich um ihre eigene Mannschaft. Sie können:

- Spieler im eigenen Kader verwalten
- Termine anlegen und bearbeiten
- Spielberichte erfassen
- Eigene Trainingsübungen anlegen
- Scouting-Einträge für ihre Mannschaft erstellen
- Statistiken ihrer Mannschaft einsehen

Ein Trainer kann keine Übungen direkt löschen – er kann nur eine Löschanfrage stellen, über die der Administrator entscheidet.

---

## 3. Verein & Mannschaft

### Verein anlegen

Jeder angemeldete Nutzer kann einen neuen Verein anlegen. Er gibt dem Verein einen Namen, optional ein Logo und eine kurze Beschreibung. Der Ersteller wird automatisch zum Vereinsadministrator.

**Wichtig:** Jeder Verein bekommt einen **einmalig generierten 6-stelligen Einladungscode**, den nur der Administrator sehen kann.

### Einem Verein beitreten

Um einem Verein beizutreten, braucht man:

1. Den **genauen Namen** des Vereins
2. Den **6-stelligen Einladungscode** (nur Administratoren können ihn sehen)

Ist beides eingegeben, ist man sofort Mitglied des Vereins als Trainer.

### Mannschaft anlegen

Der Vereinsadministrator legt Mannschaften an (z. B. U13, U15, Herren). Jede Mannschaft hat:

- Einen Namen
- Optional: Altersgruppe und Saison
- Eine **Standard-Spielzeit** (z. B. 90 Minuten für Erwachsene, 60 Minuten für Jugend)
  - Diese wird automatisch bei Spielberichten vorausgefüllt
  - Kann pro Spiel angepasst werden

### Einer Mannschaft beitreten

Genauso wie beim Verein: Name + 6-stelliger Code, und schon ist man dabei.

---

## 4. Kader – Spieler verwalten

### Spieler anlegen

Für jeden Spieler werden folgende Daten erfasst:

- **Vorname, Nachname**
- **Position** auf dem Feld: TW (Torwart), IV (Innenverteidiger), LV/RV (Außenverteidiger), DM (Defensives Mittelfeld), ZM (Zentrales Mittelfeld), LA/RA (Außenstürmer), OM (Offensives Mittelfeld), ST (Stürmer)
- **Trikotnummer**
- **Geburtsdatum** (wird berechnet: Alter + Tage bis Geburtstag)
- **Status**: Verfügbar / Verletzt / Gesperrt

### Spielerstatus

Der Status zeigt auf einen Blick, wer für das nächste Training oder Spiel verfügbar ist:

| Status | Bedeutung | Farbe |
|--------|-----------|-------|
| ✅ Verfügbar | Spieler kann eingesetzt werden | Grün |
| 🤕 Verletzt | Spieler ist verletzt und fehlt | Rot |
| 🟥 Gesperrt | Spieler ist gesperrt (z. B. nach Roter Karte) | Orange |

---

## 5. Terminkalender

### Termintypen

TrainerPro unterscheidet fünf Termintypen:

| Typ | Beschreibung |
|-----|-------------|
| **Training** | Reguläre Trainingseinheit |
| **Spiel** | Pflichtspiel (Meisterschaft, Pokal) |
| **Testspiel** | Freundschaftsspiel |
| **Turnier** | Turnier mit mehreren Einzelspielen |
| **Aktivität** | Sonstige Mannschaftsaktivität |

### Wiederkehrende Termine (Serien)

Anstatt jede Trainingsstunde einzeln einzutragen, können Serien angelegt werden. Beispiel: „Jeden Dienstag und Donnerstag Training bis Ende der Saison" – einmal eintragen, fertig.

Wenn ein einzelner Termin einer Serie geändert werden muss (z. B. weil das Feld nicht verfügbar ist), kann genau dieser eine Termin separat bearbeitet werden, ohne die gesamte Serie zu verändern.

Es ist auch möglich, alle folgenden Termine ab einem bestimmten Datum auf einmal anzupassen – zum Beispiel wenn die Trainingszeit dauerhaft geändert wird.

### Spielzeit pro Termin

Wenn ein Spiel oder Testspiel angelegt wird, wird die Spielzeit automatisch aus den Mannschaftseinstellungen übernommen (z. B. 60 Minuten für U13). Die Spielzeit kann für jeden einzelnen Termin angepasst werden.

---

## 6. Anwesenheitsliste

Für jeden Termin kann festgehalten werden, welche Spieler da waren:

| Status | Bedeutung |
|--------|-----------|
| ✅ Anwesend | Spieler war beim Termin dabei |
| ❌ Fehlend | Spieler war nicht da |
| 🟡 Entschuldigt | Spieler hat sich abgemeldet |

**So funktioniert's:**

1. Öffne den Termin
2. Alle Kaderspieler sind automatisch vorausgefüllt
3. Markiere nur die Fehlenden
4. Speichern

---

## 7. Aufstellungsplaner

### Formationen speichern

Grundformationen wie **4-3-3**, **4-2-3-1**, **4-4-2**, **3-5-2** oder **5-3-2** können gespeichert werden. Eine Formation kann als Standard markiert werden und wird dann beim Erstellen einer neuen Aufstellung vorausgewählt.

### Aufstellung erstellen

In einem **interaktiven Spielfeld** können Spieler per **Drag & Drop** auf ihre Positionen gezogen werden. 
Für jeden Spieler kann festgelegt werden:

- **Startelf** – spielt von Anfang an
- **Bank** – ist nominiert, beginnt auf der Ersatzbank
- **Nicht nominiert** – ist nicht dabei

### Vorlagen

Eine fertige Aufstellung kann als **Vorlage gespeichert** werden und beim nächsten Spiel wiederverwendet werden. Beispiel: „4-3-3 Pressing-Formation" als Standard für alle Heimspiele.

### Verknüpfung mit Spielberichten

Wenn für ein Spiel eine Aufstellung hinterlegt ist, werden beim Erstellen des Spielberichts die Startelfspieler automatisch vorgeschlagen.

---

## 8. Spielberichte & Matchday-Protokoll

### Spiel / Testspiel

Nach einem Spiel wird ein Bericht angelegt:

- **Endstand** (Tore für uns / Tore gegen uns)
- **Heim- oder Auswärtsspiel**
- **Verknüpfung mit der Aufstellung** (optional)

Zusätzlich können **Spielereignisse** minutengenau erfasst werden:

| Ereignis | Was wird eingetragen? |
|----------|----------------------|
| ⚽ Tor | Spieler + Minute |
| 🟨 Gelbe Karte | Spieler + Minute |
| 🟨🟥 Gelb-Rote Karte | Spieler + Minute |
| 🟥 Rote Karte | Spieler + Minute |
| 🔄 Auswechslung | Raus-Spieler + Rein-Spieler + Minute |

**Spieler-Auswahl:** Falls eine Aufstellung vorhanden ist, werden die Spieler in dieser Reihenfolge vorgeschlagen:

1. Startelf
2. Auswechselspieler
3. Rest des Kaders

Ohne Aufstellung: Der gesamte verfügbare Kader wird angeboten.

### Turnier

Bei Turnieren werden alle **Einzelspiele des Tages** erfasst:

- Gegner, Ergebnis, Phase (Gruppenphase, Halbfinale, Finale usw.)
- Spielzeit pro Einzelspiel
- Notizen

Am Ende des Turniers werden festgehalten:

- **Endplatzierung** (z. B. Platz 3)
- Ob die Finalrunde erreicht wurde

**Spielzeit-Modus beim Turnier:**

- **Pro Spiel:** Jeder Spieler bekommt die Spielzeit der Spiele gutgeschrieben, in denen er aktiv war
- **Gesamtzeit:** Allen nominierten Spielern wird eine gesamte Spielzeit zugewiesen

---

## 9. Statistiken

Alle Statistiken werden **automatisch aus den Spielberichten berechnet** – es müssen keine Zahlen manuell eingetragen werden.

### Leistungstracker

Zeigt für jeden Spieler in der Saison:

- Tore gesamt und Tore pro Spiel im Durchschnitt
- Gelbe Karten, Gelb-Rote Karten, Rote Karten
- **Torschützenliste** (sortierbar)
- **Kartensünder-Liste** (sortierbar)
- Filterbar nach Spieltyp (Pflichtspiele, Testspiele, Turniere, kombinierbar)

### Spielzeittracker

Zeigt wie viele Minuten jeder Spieler gespielt hat:

- Gesamtminuten, Durchschnitt pro Spiel
- Anzahl der Einsätze
- **Auslastung in Prozent** (Wie viel der möglichen Spielzeit wurde genutzt?)
- Filterbar nach Spieltyp

### Saisonstatistik

Gesamtübersicht der Saison:

- Spiele, Siege, Unentschieden, Niederlagen, Punkte
- Tore, Gegentore, Tordifferenz, Tore pro Spiel
- **Heim- und Auswärtsperformance** getrennt
- **Turnierergebnisse:** alle Platzierungen, beste Platzierung, Finalrundeneinzüge

### Jahrgangsübersicht

- Wie alt sind die Spieler? (nach Geburtsjahr aufgeschlüsselt)
- Wer hat als nächstes Geburtstag?
- Spielerliste sortiert nach Alter
- Der Administrator sieht diese Übersicht für den **gesamten Verein**
- Trainer sehen die Übersicht pro **Mannschaft**

---

## 10. Konditionstest-Tracker

Für konditionelle Tests (Ausdauer, Sprint usw.) können Ergebnisse pro Spieler eingetragen werden. Unterstützte Testarten:

| Test | Einheit | Was wird gemessen? |
|------|---------|-------------------|
| **Cooper-Test** | Meter | Wie weit läuft ein Spieler in 12 Minuten? |
| **Sprint 30m** | Sekunden | Wie schnell läuft ein Spieler 30 Meter? |
| **Shuttle-Run** | Sekunden | Richtungswechsel-Ausdauertest |
| **Sonstiges** | Frei wählbar | Andere Tests |

Die Ergebnisse werden in einer **Tabelle angezeigt** und als **Entwicklungskurve über die Zeit visualisiert**. So sieht man sofort, ob und wie ein Spieler sich verbessert hat.

**Weitere Auswertungen:**

- **Persönliche Bestleistung** jedes Spielers (hervorgehoben mit ⭐)
- **Mannschaftsdurchschnitt** als Kurve
- **Trend:** letzter Test besser oder schlechter als der vorletzte? (+/−)
- **Rangliste** nach aktuellstem Ergebnis

---

## 11. Übungsbibliothek

Jeder Trainer kann Trainingsübungen anlegen und beschreiben:

| Feld | Beispiel |
|------|---------|
| Titel | „Passdreiecke unter Druck" |
| Kategorie | Technik / Taktik / Kondition / Torschuss / Passspiel / Aufwärmen / Sonstiges |
| Dauer | 15 Minuten |
| Spieleranzahl | 8–12 Spieler |
| Material | 4 Hütchen, 2 Bälle |
| Beschreibung | Ausführliche Erklärung der Übung |

**Sichtbarkeit:** Alle Trainer des Vereins können alle Übungen sehen.

**Löschanfrage:** Möchte ein Trainer eine seiner Übungen löschen, stellt er eine Anfrage. Der Administrator sieht diese Anfragen und entscheidet, ob die Übung endgültig gelöscht wird.

---

## 12. Scouting

Mit dem Scouting-Modul können interessante Spieler aus anderen Vereinen beobachtet und der gesamte Prozess dokumentiert werden.

### Status-Ablauf

```
beobachtet → interessant → kontaktiert → Probetraining → Zusage / Absage / Selbst abgesagt
```

### Was wird erfasst?

- **Name, Alter, aktueller Verein, Position**
- **Kontaktdaten**
- **Beschreibung** (Stärken, Beobachtungen)
- **Probetrainings** (Datum + Notizen) – werden automatisch gezählt
- **Abschlussentscheidung** mit Begründung

### Freigabe für den Verein

Ein Scout-Eintrag kann für den Vereinsadministrator **freigegeben werden**. Der Administrator sieht dann alle **freigegebenen Einträge aller Mannschaften** in einer vereinsweiten Übersicht.

---

## 13. Dashboard

Das Dashboard ist die Startseite nach der Anmeldung. Es zeigt die wichtigsten Informationen auf einen Blick:

- **Hero-Card:** Team, Verein, letztes Spiel
- **Nächste Termine** (die nächsten 3–5 Trainings, Spiele usw.)
- **Kaderstatus:** Verfügbar, Verletzt, Gesperrt (mit Counts)
- **Letzte 5 Ergebnisse** (sortiert nach Datum)
- **Topscorer** (5 beste Torschützen der Saison)
- **Nächste Geburtstage** (die nächsten 3 Spieler)

---

## 🔗 Weitere Ressourcen

- **[PROJEKTSTATUS.md](PROJEKTSTATUS.md)** – Entwicklungsstand und Roadmap

---

*TrainerPro · Öffentliches Funktions-Wiki · Alle Erklärungen ohne technisches Vorwissen · Stand: Mai 2026*
