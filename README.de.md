# Eine Einleitung in die künstliche Intelligenz

*(auch KI, artificial intelligence, AI, etc.)*

**Hinweis:** Dieses Tutorial erhebt nicht den Anspruch vollständig zu sein. Vielmehr wird hier der Ansatz des schnellen Einstiegs in das Thema verbunden mit praktischen Beispielen verfolgt. Korrekturen und Erweiterungen sind willkommen.

<!-- 
## 0. Inhalte
-->

<!-- 
* [1. Was ist künstliche Intelligenz?](#user-content-1-was-ist-künstliche-intelligenz)
* [2. Unterteilung künstliche Intelligenz](#user-content-2-unterteilung-künstliche-intelligenz)
* [3. Verwendungszweck](#user-content-verwendungszweck)
* [4. Werkzeuge](#user-content-werkzeuge)
* [5. Anwendungen](#user-content-anwendungen)
--> 

## 1. Was ist künstliche Intelligenz?

Es gibt eine Menge von Seiten und Fachliteratur, welche das Thema allumfassend gut erklären und erläutern. Allen voran der Eintrag in der Wikipedia: [Künstliche Intelligenz](https://de.wikipedia.org/wiki/K%C3%BCnstliche_Intelligenz)

Zusammengefasst lässt sich das Thema nicht wirklich ein- bzw. abgrenzen, da sich der Begriff Intelligenz weder philosophisch noch systematischen vollständig definieren lässt. Im Allgemeinen bezeichnet die "künstliche" Intelligenz ein Teilgebiet der Informatik. Ein Teilgebiet, der den Versuch unternimmt menschenähnliche (intelligente) Entscheidungsstrukturen nachzubilden. **Anders ausgedrückt:** Man simuliert z.B. mit Hilfe des Computers durch Implementation entsprechender Algorithmen und Lösungsansätze ein Verhalten, womit vorgelegte Probleme selbstständig durch Lernen, Erkennen und Ausprobieren gelöst werden können.

**Hinweis:** Nicht alle auftauchenden Themen unterhalb der künstlichen Intelligenz müssen zwangsweise mit den Begriffen der (menschlichen bzw. "echten") Intelligenz korrelieren (Stichwort: Big Data, etc.). Oft vermengen sich hier Themen so wie sich der Begriff Intelligenz auch nicht eindeutig definieren lässt.

### 1.1 Schwache künstliche Intelligenz

**Zusammengefasst:** Alle heute existierenden Systeme fallen unter die Kategorie der schwachen künstlichen Intelligenz.

Schwache künstliche Intelligenz ist auf die Erfüllung klar definierter Aufgaben ausgerichtet (Erkennen von Mustern definierter Aufgabenstellungen, Klassifizieren vorgegebener Objekte, etc.). Sie simuliert lediglich Intelligenz und nutzt dabei die Vorteile der Rechentechnik gegenüber dem menschlichem Gehirn: Berechnen und Probieren verschiedener Varianten in einem Bruchteil der Zeit und Ausgabe der "intelligentesten" Lösung (z.B. kürzester Weg von A nach B). Sie sind jedoch nicht intelligent im übertragenen Sinne.

### 1.2 Starke künstliche Intelligenz

**Zusammengefasst:** Algorithmen der Kategorie starke künstliche Intelligenz gibt es bisher noch nicht.

Das Ziel der starken künstlichen Intelligenz ist es Maschinen dazu zu bringen aus eigenem Antrieb und ohne Eingriff Probleme intelligent zu lösen. Bis heute ist es nicht gelungen derart autonome Verhaltensweisen zu implementieren. Man spricht hier von der Umsetzung deterministischer Algorithmen, welche die intellektuellen Fähigkeiten des Menschen nachahmen bzw. sogar übertreffen können.

Die Diskussionen zu diesem Thema sind zwiespältig. Sie reichen von unrealistisch bis realistisch in ein paar Jahrzehnten. Die Entwicklung neuartiger Computerarchitekturen (Quantencomputer) kann einen entscheidenden Beitrag zur Lösung dieses Ziel beitragen.

## 2. Buzzwords der künstlichen Intelligenz (Unterteilung)

* [Machine Learning](https://de.wikipedia.org/wiki/Maschinelles_Lernen)
* [Deep Learning](https://de.wikipedia.org/wiki/Deep_Learning)
* [Neuronale Netze](https://de.wikipedia.org/wiki/Neuronales_Netz)
* [Robotik](https://de.wikipedia.org/wiki/Robotik)
* [Natural Language Processing (NLP)](https://en.wikipedia.org/wiki/Natural-language_processing)

Ferner:

* [Big Data](https://de.wikipedia.org/wiki/Big_Data)
* [Suchverfahren](https://de.wikipedia.org/wiki/Suchverfahren)
* [Mustererkennung](https://de.wikipedia.org/wiki/Mustererkennung)
* (maschinelles) [Lernen](https://de.wikipedia.org/wiki/Computational_Neuroscience) (überwacht, unüberwacht, teilüberwacht, etc.)
* [Graphen-, Netzwerktheorie](https://de.wikipedia.org/wiki/Graphentheorie)

## 3. Verwendungszweck

Was ist derzeit möglich? Was nicht?

### Möglich (schwache künstliche Intelligenz)

* Analyse riesiger Datenmengen (Big Data)
  * Trennung interessanter Daten von weniger interessanten Daten
* Erkennung von Mustern
  * Texte (automatisierte Übersetzungen, Sentimentanalysen, Emotionsanalysen, Autovervollständigung und Korrekturvorschläge bei Suchvorgängen, etc.)
  * Bilder (ähnliche Bilder, Objekterkennung)
  * Tonspuren (Spracherkennung, NLP)
  * Produkte ("andere User kauften auch")
  * Verhalten (Individuelle Aussteuerung von Werbung, Handlungsempfehlungen auf Basis einer Wissensdatenbank, Bonitätsberechnung der Banken, etc.)
  * Auswertung anderer Analysedaten (Machinen, z.B. beim autonomen Fahren, etc.)
* Ermittlung der optimalsten Lösung
  * Routenplanung (kürzester Weg von A nach B)
  * Computerspiele (Computergegner, Schach, Brettspiel Go, etc.)
  
### (Noch) nicht möglich

* "echte" Intelligenz (starke künstliche Intelligenz)
  * *"Lieber Computer, bitte löse mein Ticket mit der Nummer xy!"*

## 4. Werkzeuge

Frameworks und Tools, welche bei dem Thema künstliche Intelligenz unterstützen bzw. Technologien der KI nutzen:

* [TensorFlow](https://www.tensorflow.org/) (ehemals DistBelief; Google)
* [Caffe](http://caffe.berkeleyvision.org) (Deep Learning Framework)
* [Keras](https://keras.io) (Python Deep Learning library)
* [Apache MXNet](https://mxnet.incubator.apache.org) (A flexible and efficient library for deep learning)
* [Gluon](https://aws.amazon.com/de/blogs/aws/introducing-gluon-a-new-library-for-machine-learning-from-aws-and-microsoft) (library for machine learning)
* [PyTorch](https://pytorch.org)
* [DL4J](https://deeplearning4j.org)

## 5. Anwendungen

* [Google Photo](https://photos.google.com) ("smarte" Bilderkennung)
* [Google Translate](https://translate.google.com) (automatische Übersetzungen)
* [Google AutoDraw](https://www.autodraw.com) (Erkennung handschriftlicher Zeichungen)
* [Microsoft Captionbot](https://www.captionbot.ai) (automatische Bild-Objekterkennung)
* Facebook [FBLearner Flow](https://code.facebook.com/posts/1072626246134461/introducing-fblearner-flow-facebook-s-ai-backbone/) und FBLearner Predictor (Übersetzung Posts, Klassifizierung Fotos, Auslieferung passender Werbung)
* [IBM Watson](https://de.wikipedia.org/wiki/Watson_(K%C3%BCnstliche_Intelligenz)) (Fragenbeantwortung)
* [Apple Core ML](https://developer.apple.com/documentation/coreml) (Gesichtserkennung)
* [Amazon DSSTNE](https://github.com/amzn/amazon-dsstne) (Alexa)

## 6. Chancen und Gefahren der künstlichen Intelligenz

### 6.1. Chancen

* TODO..

### 6.2. Gefahren

* Arbeiten können durch Maschinen vollständig autonom übernommen werden: bestimmte Berufe werden überflüssig
  * https://www.mobilegeeks.de/news/google-creatism-diese-ki-koennte-auch-foto-experten-den-job-kosten/
* Mögliche Fehlschlüsse von Berechnungen bzw. nicht alle Berechnungen sind transparent: "Ist der Betroffene wirklich nicht kreditwürdig?"

## A. Literatur

* [Praxiseinstieg Deep Learning](https://www.oreilly.de/buecher/12840/9783960090540-praxiseinstieg-deep-learning.html)
* [Machine Learning – kurz & gut](https://www.oreilly.de/buecher/12870/9783960090526-machine-learning-%E2%80%93-kurz-%26-gut.html)
* [Neuronale Netze selbst programmieren](https://www.oreilly.de/buecher/12892/9783960090434-neuronale-netze-selbst-programmieren.html)

## B. Authors

* Björn Hempel <bjoern@hempel.li> - _Initial work_ - [https://github.com/bjoern-hempel](https://github.com/bjoern-hempel)

## C. License

This tutorial is licensed under the MIT License - see the [LICENSE.md](/LICENSE.md) file for details
