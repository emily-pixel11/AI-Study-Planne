# AI Study Planner
Building AI course project

---

## Zusammenfassung

AI Study Planner ist ein KI-gestütztes Tool, das Schülern und Studenten hilft, personalisierte Lernpläne zu erstellen. Basierend auf verfügbaren Lernzeiten, Prüfungsdaten und Schwierigkeitsgraden der Fächer erstellt die KI optimierte Zeitpläne.

Das Ziel ist es, Stress zu reduzieren und die Lernorganisation zu verbessern.

---

## Hintergrund

Viele Lernende haben Schwierigkeiten mit:

* Zeitmanagement
* Motivation
* Prüfungsstress
* Priorisierung von Aufgaben

Oft lernen Menschen ineffizient oder beginnen zu spät mit der Vorbereitung.

Meine Motivation für dieses Projekt ist es, Lernen strukturierter und einfacher zu machen. KI kann helfen, individuelle Lernpläne automatisch anzupassen.

---

## Wie wird es verwendet?

Benutzer geben folgende Informationen ein:

* Fächer
* Prüfungsdaten
* Verfügbare Lernstunden
* Schwierigkeitsgrad

Die KI analysiert die Daten und schlägt einen Lernplan vor.

Beispiel:

| Fach       | Schwierigkeit | Stunden pro Woche |
| ---------- | ------------- | ----------------- |
| Mathematik | Hoch          | 8                 |
| Englisch   | Mittel        | 4                 |
| Geschichte | Niedrig       | 2                 |

---

## Bilder

## Beispiel eines KI-Lernplans

![Study Planner](https://images.unsplash.com/photo-1522202176988-66273c2fd55f)

## KI und Lernen

![AI Education](https://images.unsplash.com/photo-1516321318423-f06f85e504b3)

---

## Datenquellen und KI-Methoden

Das Projekt verwendet:

* Benutzereingaben
* Lernzeiten
* Prüfungstermine
* Prioritäten

Mögliche KI-Methoden:

* Empfehlungssysteme
* Planungsalgorithmen
* Maschinelles Lernen
* Optimierungsalgorithmen

---

## Beispielcode

```python
subjects = {
    "Mathematik": 8,
    "Englisch": 4,
    "Geschichte": 2
}

print("Empfohlene Lernstunden pro Woche:\n")

for subject, hours in subjects.items():
    print(f"{subject}: {hours} Stunden")
```

---

## Erweiterter KI-Beispielcode

```python
import random

subjects = [
    "Mathematik",
    "Physik",
    "Englisch",
    "Informatik"
]

print("KI-generierter Lernplan:\n")

for subject in subjects:
    hours = random.randint(2, 8)
    print(f"{subject}: {hours} Stunden Lernen")
```

---

## Herausforderungen

Dieses Projekt löst nicht alle Probleme:

* Menschen lernen unterschiedlich
* Motivation kann nicht vollständig automatisiert werden
* KI-Vorschläge sind nicht immer perfekt

Außerdem müssen Datenschutz und verantwortungsvoller Umgang mit Nutzerdaten berücksichtigt werden.

---

## Wie geht es weiter?

Zukünftige Verbesserungen:

* Mobile App
* Kalenderintegration
* Erinnerungsfunktionen
* Fortschrittsanalyse
* Adaptive KI-Vorschläge
* Integration mit ChatGPT APIs

---

## Anerkennung

Inspiriert von:

* KI-Lernplattformen
* Productivity Apps
* OpenAI
* Building AI Kurs

Verwendete Bilder stammen von Unsplash.
