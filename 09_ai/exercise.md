# 9. Künstliche Intelligenz - Übungen

## 9.1 Robotergesetze
Isaac Asimov definierte in der Kurzgeschichte "Runaround" bereits 1942 die drei sogenannten _Robotergesetze_. Wie lauten diese?


## 9.2 Turing Test
Erläutern Sie, was man unter dem Turing-Test versteht. Wann und wo wurde er erstmals beschrieben und wie läuft er ab?


## 9.3 Captcha
Heute müssen Internet-Benutzer häufig sogenannte Captchas lösen, um sich bei Webseiten anzumelden. In welchem Zusammenhang stehen Captchas zum Turing-Test?


## 9.4 Typologie künstlicher Intelligenz
Man unterscheidet häufig _vier Typen_ (oder Stufen) von künstlicher Intelligenz. Bitte erläutern Sie diese kurz.


## 9.5 Schwache vs. Starke KI
Erläutern Sie den Unterschied zwischen einer _schwachen_ und einer _starken_ KI.


## 9.6 Superintelligenz
Definieren Sie kurz in eigenen Worten, was man unter einer _Superintelligenz_ versteht.


## 9.7 Möglichkeiten und Grenzen der KI
Recherchieren Sie in der KI-Literatur bzw. im Internet, inwiefern folgende Probleme heutzutage mittels Computer- bzw. Robotereinsatz gelöst werden können:

  1. Spielen der Brettspiele Dame und Go
  2. Verarbeiten natürlicher Sprache in Echtzeit
  3. Autonomie unbemannter Fahr- und Flugzeuge (UGVs und UAVs)
  4. Automatische Gesichtserkennung
  5. Spielen von Computerspielen (z.B. klassische Atari-Spiele) wie ein Mensch.
  6. Komponieren von Musik.
  7. Turing-Test

Schreiben Sie Ihre Erkenntnisse in jeweils 2–3 Sätzen auf.


## 9.8 Arten des maschinellen Lernens
Definieren Sie in kurzen Sätzen die folgenden Arten des maschinellen Lernens:

  1. _Überwachtes Lernen_ (_supervised learning_)
  2. _Unüberwachtes Lernen_ (_unsupervised learning_)
  3. _Bestärkendes Lernen_ (_reinforced learning_)


## 9.9 Machine Learning: Begriffe
Bitte definieren Sie in Ihren eigenen Worten kurz die folgenden zentralen Begriffe aus dem Machine Learning:

  1. Features
  2. Klassifikation (classification)
  3. Trainingsdaten (training data)
  4. Label
  5. Labeled Data / Unlabeled Data
  6. Decision Boundaries
  7. Entscheidungsbaum (decision tree)
  8. Forest
  9. Confusion Matrix


## 9.10 Neuron
Ein künstliches Neuronales Netz besteht aus sogenannten _künstlichen Neuronen_. Erläutern Sie kurz, wie ein solches Neuron funktioniert.


## 9.11 Entscheidungsbaum erstellen
Gegeben sind Messwerte für das Gewicht und den Durchmesser von Mandarinen, Orangen und Zitronen, die als CSV-Dateien vorliegen:

  1. Mandarinen: [mandarine.csv](data/mandarine.csv)
  2. Orangen: [orange.csv](data/orange.csv)
  3. Zitrone: [zitrone.csv](data/zitrone.csv)

_Zeichnen_ Sie die Daten in einem Diagramm und definieren Sie dann basierend darauf einen _Classifier_ in Form eines Entscheidungsbaums, der aufgrund von Gewicht und Größe die Daten den drei Klassen "Mandarine", "Orange" oder "Zitrone" zuordnet.

Tipp: Die Daten lassen sich sehr leicht mit dem Werkzeug [GNUPlot](http://www.gnuplot.info) in einem Diagramm ausgeben.

Wie viele Objekte (Obststücke) aus den Beispieldateien werden durch Ihren Classifier _richtig_, wie viele _falsch_ klassifiziert?

Sie finden ein _unbekanntes Objekt_ in einem Obstkorb, mit einer Masse von 140g und einem Durchmesser von 6cm. Um was handelt es sich Ihrer Meinung nach?


## 9.12 Berechnungen an einem Neuron
Gegeben sei ein künstliches Neuron mit drei Eingängen (x1, x2 und x3) (und einem Ausgang a). Die Gewichte für die drei Eingänge sind:

`(w1, w2, w3) = (0.3, 0.5, 0.2)`

Als Aktivierungsfunktion wird die Sigmoid-Funktion verwendet, wobei vorher noch ein Bias addiert wird. Der Bias beträgt konstant -2.0. Den Verlauf der Sigmoid-Funktion `f` für das Neuron können Sie aus folgender Grafik ableiten (`f(x) = 1 / (1 + exp(-x))`):

<img src="img/sigmoid.png" width="500">

Berechnen Sie für folgende Werte die Ausgabe des Neurons:

`(x1, x2, x3) = (4.3, 2.6, 2.0)`


