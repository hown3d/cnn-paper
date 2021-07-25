# Convolutional Neural Networks

Lukas Höhl, Yuki Shiono

---

## Inhaltsverzeichnis
1. Einleitung 
2. Grundlagen von Neural Networks
3. Convolutional Neural Networks
4. State of the Art
5. Ausblick

---

## Einleitung

* Kern von Deep Learning
* Nervensystem von Lebewesen als Vorbild
* Einsatzbeispiele: Bildklassifizierung von Google Images, Videoempfehlungen auf Youtube oder auch KIs für Brettspiele wie Go (AlphaGo von DeepMinds)

---

## Grundlagen von Neural Networks

![Neural Networks](neural-network-diagram.svg)

---

## Dense Layer
* ein mögliches Hidden Layer
* alle Neuronen sind mit allen Neuronen des vorherigen Layers verbunden
    * Fully Connected Layer
* wird zur Klassifikation genutzt
    * entsprechend Anzahl Neuronen gleich Anzahl Kategorien


---

## State of the Art
* Einschränkung auf Image Classification
* Festlegung durch Benchmark-Datasets
* Beispiele ImageNet, CIFAR-10, CIFAR-100, MNIST, etc.

---

### CIFAR-10
* 10 Kategorien (Flugzeug, Auto, Vogel, Katze, Reh, Frosch, Pferd, Schiff und LKW)
* je 6.000 Farbfotos (32x32 Pixel)

---

### ImageNet
* WordNet als Grundlage
* Ziel: 500-1000 hochauflösende Bilder pro Synset
* ImageNet Large Scale Visual Recognition Challenge
    * 1000 Kategorien aus dem Bestand 
    * keine Überlappung der Synset

---

## EffcientNet
* Grundarchitektur: 2019 von Mingxing Tan und Quoc Le
* im Zuge einer neuen Skalierungsmethode entwickelt
* höhere Genauigkeit mit weniger Parameter
* EfficientNet-L2 von Pierre Foret, Ariel Kleiner, Hossein Mobahi und Behnam Neyshabur aus dem Jahr 2020
    * aktuell bestabschneidenstes CNN in Benchmark mit CIFAR-10, CIFAR-100
    * EfficientNet als Basis

---

## Ausblick
* Transformer
    * Ursprung: Natural Language Processing
    * schneidet in den Bechmark-Datasets besser als CNN ab
    * besonders für große Datasets geeignet
