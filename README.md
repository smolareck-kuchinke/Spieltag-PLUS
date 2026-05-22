# Spieltag-PLUS

Spieltag PLUS ist eine digitale Plattform für Fußballvereine, Fans und Stadionbetreiber mit Funktionen für Ticketing, Community, Sicherheit, KI-Analysen und Spieltagsmanagement.
Alles in einem! 


# OOD-E1 – Event Storming

## 1. Wildes Brainstorming

In der ersten Phase des Event Stormings habe ich fachliche Domain Events gesammelt.  
Die Events wurden zunächst unsortiert erfasst, um Prozesse, Abläufe und mögliche fachliche Zusammenhänge sichtbar zu machen.

Dabei wurden unterschiedliche Bereiche berücksichtigt:
- Ticketing
- Spielbetrieb
- Stadionbetrieb
- Sicherheit
- Community
- KI-gestützte Analysen

### Screenshot

![Wildes Brainstorming](images/wildes-brainstorming.png)

---

## 2. Zeitliche Sortierung

In der zweiten Phase habe ich die Domain Events zeitlich sortiert.  
Dadurch wurden erste Prozessketten, fachliche Zusammenhänge und mögliche Domaingrenzen sichtbar.
Die zeitliche Sortierung stellt bei mir keine vollständig lineare Prozesskette dar.  
Es sind mehrere parallele fachliche Abläufe und Event-Ströme sichtbar vor allem bei den KI und Community-Prozessen.

Domains:
- Ticketing-Prozesse
- Stadionzugang
- Spielbetrieb
- Community-Funktionen
- Sicherheits- und KI-Prozesse

### Screenshot

![Zeitliche Sortierung](images/zeitsortierung.png)

---

## 3. Transition Borders & Domains

In der dritten Phase des Event Stormings habe ich einzelne Domains identifiziert:

- Benutzerverwaltung
- Ticketing
- Stadionzugang
- Spielbetrieb
- Community 
- Sicherheit
- KI 

Zusätzlich wurden Hotspots ergänzt, um offene Fragen, Risiken und Unsicherheiten innerhalb der Domain sichtbar zu machen.

-Verifizierung von Usern
- Erkennung gefälschter Tickets
- Rückerstattungen
- Moderation problematischer Kommentare
- Ki-Erkennung
- Verarbeitung von Sicherheitsvorfällen
- Synchronisieurng von Live-Daten
  

### Screenshot

![Transition Borders](images/transitionborders.png)


# OOD-E2 – Core Domain Chart

Für Spieltag PLUS wurden die identifizierten Domains anhand von Business Differentiation ujd Model Complexity analysiert und eingeordnet.

## Core Domains

### Spielbetrieb
Der Spielbetrieb bildet das zentrale Herzstück der Plattform.  
Live-Spielereignisse, Echtzeitdaten und Spielanalysen erzeugen den größten fachlichen Mehrwert.

### KI 
KI-gestützte Analysen, Crowd Detection und personalisierte Empfehlungen stellen ein wesentliches Unterscheidungsmerkmal gegenüber klassischen Stadion- oder Ticketplattformen dar.

---

## Supporting Domains

### Ticketing
Ticketing ist wichtig für die Plattform, stellt jedoch keine einzigartige Kernfunktion dar.

### Community 
Die Community erhöht die Nutzerbindung, ist jedoch unterstützend zum eigentlichen Spieltagserlebnis.

### Stadionzugang
Der Stadionzugang unterstützt den operativen Ablauf des Spieltags.

### Sicherheit & Moderation
Sicherheits- und Moderationsfunktionen sind wichtig für Stabilität und Compliance.

---

## Generic Domains

### Benutzerverwaltung
Benutzerverwaltung ist eine generische Standardfunktion und könnte durch externe Lösungen bereitgestellt werden.
