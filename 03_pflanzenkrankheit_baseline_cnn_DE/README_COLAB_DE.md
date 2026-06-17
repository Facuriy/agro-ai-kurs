# Colab-Start: Pflanzenkrankheit mit Baseline und Mini-CNN

## Schnellstart

1. Öffne `Pflanzenkrankheit_Mini_CNN_Klasse_DE.ipynb` in Google Colab.
2. Lade den Ordner `mini_disease_dataset/` mit hoch.
3. Colab hat PyTorch meistens vorinstalliert. Falls etwas fehlt:

```python
!pip -q install numpy pandas matplotlib pillow scikit-learn torch torchvision
```

4. Dann `Runtime > Run all`.

## Slim-Dataset

Dieses Paket enthält nur 100 Bilder: 5 Klassen x 20 Bilder. Die Bilder sind 96x96 JPEGs.
Das ist absichtlich klein, damit die Klasse schnell läuft. Für Forschung ist es nicht gedacht.

## Varianten

- `Pflanzenkrankheit_Mini_CNN_STUDENT_DE.ipynb`: Version für Studierende, ohne Dozentenhinweise.
- `Pflanzenkrankheit_Mini_CNN_DOZENT_DE.ipynb`: Version für Lehrende, mit Ablauf, Lösungsskizze und Diskussionspunkten.
- `Pflanzenkrankheit_Mini_CNN_Klasse_DE.ipynb`: technische Basisversion, bleibt für Rückverfolgbarkeit erhalten.
