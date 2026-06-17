# Colab-Start: Fernerkundung, Drohne und Vegetationsindizes

## Schnellstart

1. Öffne `Fernerkundung_Drohne_Vegetationsindizes_Klasse_DE.ipynb` in Google Colab.
2. Lade den Ordner `class_data_remote_sensing/` in dieselbe Colab-Session hoch.
3. Falls Pakete fehlen:

```python
!pip -q install numpy pandas matplotlib
```

4. Dann `Runtime > Run all`.

## Warum ist das Paket klein?

Das originale GeoTIFF wurde auf einen kleinen 256x256-Ausschnitt reduziert und als `.npz`
gespeichert. Das reicht für die Lehre: Bänder, NDVI, NDRE, Auflösung und einfache Alarmkarten.

## Varianten

- `Fernerkundung_Drohne_Vegetationsindizes_STUDENT_DE.ipynb`: Version für Studierende, ohne Dozentenhinweise.
- `Fernerkundung_Drohne_Vegetationsindizes_DOZENT_DE.ipynb`: Version für Lehrende, mit Ablauf, Lösungsskizze und Diskussionspunkten.
- `Fernerkundung_Drohne_Vegetationsindizes_Klasse_DE.ipynb`: technische Basisversion, bleibt für Rückverfolgbarkeit erhalten.
