# Agro-AI Kurs

Willkommen! Dieses Repository enthält drei kleine, praktische Übungen für den Unterricht.

Die Notebooks laufen direkt im Browser. Die kleinen Datensätze werden beim Start automatisch geladen.

## Schnellstart

1. Einen Link unten öffnen.
2. In Colab oder Binder warten, bis das Notebook geladen ist.
3. Oben im Menü auf `Runtime > Run all` klicken.

## Welche Option soll ich nehmen?

| Option | Wann benutzen? |
|---|---|
| **Colab** | Empfohlen, wenn ein Google-Konto vorhanden ist. Startet meistens schneller. |
| **Binder** | Alternative ohne Google-Konto. Der Start kann einige Minuten dauern. |

## Übungen

### 1. Fernerkundung, Drohne und Vegetationsindizes

Themen: RGB, Falschfarbe, NIR, RedEdge, NDVI, NDRE, Auflösung, einfache Alarmkarte.

[In Colab öffnen](https://colab.research.google.com/github/Facuriy/agro-ai-kurs/blob/main/01_fernerkundung_drohne_indices_DE/Fernerkundung_Drohne_Vegetationsindizes_DOZENT_DE.ipynb)

[In Binder öffnen](https://mybinder.org/v2/gh/Facuriy/agro-ai-kurs/main?labpath=01_fernerkundung_drohne_indices_DE/Fernerkundung_Drohne_Vegetationsindizes_DOZENT_DE.ipynb)

### 2. Pflanzenzählung mit Computer Vision

Themen: Excess Green, Schwellenwert, Morphologie, Connected Components, Ground Truth, Precision, Recall, F1.

[In Colab öffnen](https://colab.research.google.com/github/Facuriy/agro-ai-kurs/blob/main/02_pflanzenzaehlung_computer_vision_DE/Pflanzenzaehlung_Programmierung_DOZENT_DE.ipynb)

[In Binder öffnen](https://mybinder.org/v2/gh/Facuriy/agro-ai-kurs/main?labpath=02_pflanzenzaehlung_computer_vision_DE/Pflanzenzaehlung_Programmierung_DOZENT_DE.ipynb)

### 3. Pflanzenkrankheit mit Baseline und Mini-CNN

Themen: Bildklassifikation, Trainingsdaten, Baseline, Random Forest, kleine CNN, Confusion Matrix, Overfitting.

[In Colab öffnen](https://colab.research.google.com/github/Facuriy/agro-ai-kurs/blob/main/03_pflanzenkrankheit_baseline_cnn_DE/Pflanzenkrankheit_Mini_CNN_DOZENT_DE.ipynb)

[In Binder öffnen](https://mybinder.org/v2/gh/Facuriy/agro-ai-kurs/main?labpath=03_pflanzenkrankheit_baseline_cnn_DE/Pflanzenkrankheit_Mini_CNN_DOZENT_DE.ipynb)

## Ordner

```text
00_leerer_ordner/
klassen/
01_fernerkundung_drohne_indices_DE/
02_pflanzenzaehlung_computer_vision_DE/
03_pflanzenkrankheit_baseline_cnn_DE/
```

- `00_leerer_ordner/`: leerer Platzhalterordner.
- `klassen/`: kurze Übersicht der drei Übungen.
- Die drei nummerierten Ordner enthalten die Notebooks und kleinen Datensätze.

## Hinweis

Binder braucht kein Google-Konto, ist aber manchmal langsam. Für die dritte Übung mit der Mini-CNN ist Colab meistens angenehmer.

Wenn etwas nicht startet: Seite neu laden und noch einmal `Run all` ausführen.
