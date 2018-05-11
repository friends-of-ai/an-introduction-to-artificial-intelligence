# Eine Einleitung in die künstliche Intelligenz

*(auch KI, artificial intelligence, AI, etc.)*

**Hinweis:** Dieses Tutorial erhebt nicht den Anspruch vollständig zu sein. Vielmehr wird hier der Ansatz des schnellen Einstiegs in das Thema verbunden mit praktischen Beispielen verfolgt. Korrekturen und Erweiterungen sind willkommen.

Weitere praktische Beispiele befinden sich im Kapitel: [A. Weiterführende Tutorials](#user-content-a-weiterführende-tutorials).

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

Es gibt eine Menge von Seiten und Fachliteratur, welche das Thema allumfassend gut erklären und erläutern. Allen voran der Eintrag in der Wikipedia: [Künstliche Intelligenz](https://de.wikipedia.org/wiki/K%C3%BCnstliche_Intelligenz). Weitere Querverweise befinden sich in den Quellenangaben bzw. auch an den entsprechenden Stellen in diesem Dokument.

Zusammenfassend lässt sich das Thema nicht wirklich ein- bzw. abgrenzen, da sich der Begriff Intelligenz weder philosophisch noch systematischen vollständig definieren lässt. Im Allgemeinen bezeichnet die "künstliche" Intelligenz ein Teilgebiet der Informatik. Ein Teilgebiet, der den Versuch unternimmt menschenähnliche (intelligente) Entscheidungsstrukturen nachzubilden. **Anders ausgedrückt:** Man simuliert z.B. mit Hilfe des Computers durch Implementation entsprechender Algorithmen und Lösungsansätze ein Verhalten, mit welchem vorgelegte Probleme selbstständig durch Lernen, Erkennen und Ausprobieren gelöst werden können (z.B. die Einsortierung von Bildern, das Verstehen von gesprochener Sprache, etc.).

Auf dem Gebiet der künstlichen Intelligenz wird schon seit einigen Jahrzehnten geforscht. Die Algorithmen und Vorgehensweisen unterscheiden sich heute dabei generell gesehen gar nicht so grundlegend von den Vorgehensweisen vor rund 20 Jahren. Was den Hype und den Erfolg dieser Verfahren heutzutage ausmacht ist das Vorhandensein enormer Rechenleistung (z.B. ganzer Rechenzentren), der Zugang zu unzähligen und kostengünstigen "menschlichen" Ressourcen (durch die Nutzung von Internetdiensten wie Google, Microsoft, facebook, etc.), sowie eine schier unendlich verfügbare Menge an schon vorhandenen Daten. Ob die Daten dabei schon klassifiziert oder noch zu klassifizieren sind, ob sie aktuell in diesem Moment auf unzähligen Plattformen generiert werden oder auf Google zum Download bereitstehen, spielt hierbei erstmal keine Rolle. Fakt ist: Daten sind zu Genüge vorhanden! (Stichwort: Daten sind das neue Öl)

Verändert hat sich heute die Herangehensweise an das Thema. Was vor einigen Jahrzehnten mit dem Schreiben "einiger Zeilen Computercode" begann, erfordert heute weitergehende Wissenschaften. Das Verstehen und die Erforschung des menschlichen Denkens scheint ein weiteres Schlüsselwort zu sein, um auf dem Gebiet erfolgreich weiter vorran zu kommen (neuronale Netze seit 2012). Die Teilgebiete der Informatik arbeiten demzufolge oft Hand in Hand mit den Fachgebieten der Neurologie und Psychologie zusammen.

**Hinweis:** Nicht alle auftauchenden Themen unterhalb der künstlichen Intelligenz müssen zwangsweise mit den Begriffen der (menschlichen bzw. "echten") Intelligenz korrelieren (Stichwort: Big Data, etc.). Dennoch dürfen sie der künstlichen Intelligenz zugeordnet werden. Oft vermengen sich hier Themen beider Teilbereiche so wie sich der Begriff Intelligenz auch nicht eindeutig definieren lässt.

### 1.1 Schwache künstliche Intelligenz

**Zusammengefasst:** Alle heute existierenden Systeme und Vorgehensweisen fallen unter die Kategorie der schwachen künstlichen Intelligenz.

Schwache künstliche Intelligenz ist auf die Erfüllung klar definierter Aufgaben (Domänen) ausgerichtet. Z.B.: Erkennung von Mustern definierter Aufgabenstellungen, Klassifizierung vorgegebener Objekte, etc. Sie simuliert lediglich Intelligenz und nutzt dabei die Vorteile der Rechentechnik gegenüber dem menschlichem Gehirn: Berechnen und Probieren verschiedener Varianten in einem Bruchteil der Zeit und Ausgabe der "intelligentesten" Lösung (z.B. kürzester Weg von A nach B). Sie sind jedoch nicht intelligent im übertragenen Sinne.

### 1.2 Starke künstliche Intelligenz

**Zusammengefasst:** Algorithmen der Kategorie "starke künstliche Intelligenz" gibt es bisher noch nicht.

Das Ziel der starken künstlichen Intelligenz ist es Maschinen dazu zu bringen aus eigenem Antrieb und ohne Eingriff Probleme intelligent zu lösen. Bis heute ist es nicht gelungen derart autonome Verhaltensweisen zu implementieren. Man spricht hier von der Umsetzung deterministischer bzw. sogar indeterministischer Algorithmen, welche die intellektuellen Fähigkeiten des Menschen nachahmen bzw. sogar übertreffen können. Ein Ansatz dazu könnte sein alle bekannten Domänen (und darüber hinaus) intelligent zusammenzufassen. Der Maschine Anhaltspunkte mitzugeben, sich fehlendes Wissen (die Domänen) selbstständig anzueignen, sofern ihr diese für die Erfüllung der aktuellen Aufgabe fehlen.

Die Diskussionen zu diesem Thema sind zwiespältig. Sie reichen von unrealistisch bis realistisch in ein paar Jahrzehnten. Die Entwicklung neuartiger Computerarchitekturen (Quantencomputer) kann einen entscheidenden Beitrag zur Lösung dieses Ziel beitragen.

## 2. Buzzwords der künstlichen Intelligenz (Unterteilung der KI)

* [Künstliche Intelligenz](https://de.wikipedia.org/wiki/K%C3%BCnstliche_Intelligenz)
  * Künstliche Intelligenz ist der Oberbegriff zur Beschreibung aller Forschungsfelder, die sich mit der Erbringung menschlicher Intelligenzleistungen durch Maschinen beschäftigen
* [Machine Learning](https://de.wikipedia.org/wiki/Maschinelles_Lernen)
  * Ist ein Oberbegriff für alle Verfahren des maschinellen Lernens
  * Das maschinelle Lernen bedeutet die selbständige Generierung von Erfahrungen aus Wissen bzw. schon analysierten bekannten Datensätzen
  * **Anders ausgedrückt:** Mit den Methoden des Machine Learnings können Vorhersagen aus schon bekannten Dingen (Analysen) getroffen werden (induktives Lernen).
* [Deep Learning](https://de.wikipedia.org/wiki/Deep_Learning)
  * Deep Learning ist die Königsdisziplin des maschinellen Lernens und wahrscheinlich die bedeutendste Zukunftstechnologie innerhalb des Themas "künstlicher Intelligenz"
  * Es ist ein Verfahren analog dem Machine Learning, jedoch unter Einbeziehung statistischer Methoden (in Verbindung mit neuronalen Netzen, etc.)
  * **Anders ausgedrückt:**
    * Machine Learning: Vorhersagen durch vordefinierte Algorithmen (assisted learning)
    * Deep Learning: geht einen Schritt weiter. Die entsprechenden Algorithmen werden gelernt und permanent durch Anwendung weiter verfeinert und verbessert. Vorhersagen stammen dann aus diesen automatisch gelernten Algorithmen. Die Maschine findet unter Umständen Dinge, die wir nicht gesucht / erwartet haben.
* [(Künstliche) Neuronale Netze](https://de.wikipedia.org/wiki/K%C3%BCnstliches_neuronales_Netz)
  * Sind eine Simulierung und Nachahmung neuronaler Netze nach biologischem Vorbild
  * Dieses Netz besteht z.B. aus unzähligen Neuronen
  * Ein einzelnes (künstliches) Neuron verarbeitet verschiedene Eingangssignale und gibt (feuert) ein Ausgangssignal nach einem vordefinierten Kriterium (Schwellenwert, Häufigkeit, Muster, etc.)
* [Robotik](https://de.wikipedia.org/wiki/Robotik)
  * Die Robotik ist grob gesagt die "Hardware" (Ein- und Ausgabe) der künstlichen Intelligenz
* [Natural Language Processing (NLP)](https://en.wikipedia.org/wiki/Natural-language_processing)
  * NLP befasst sich mit der Verarbeitung sowie der Ausgabe natürlicher Sprache in geschriebener und gesprochener Form

Ferner:

* [Big Data](https://de.wikipedia.org/wiki/Big_Data)
* [Suchverfahren](https://de.wikipedia.org/wiki/Suchverfahren)
* [Mustererkennung](https://de.wikipedia.org/wiki/Mustererkennung)
* (maschinelles) [Lernen](https://de.wikipedia.org/wiki/Computational_Neuroscience) (überwacht, unüberwacht, teilüberwacht, etc.)
* [Graphen-, Netzwerktheorie](https://de.wikipedia.org/wiki/Graphentheorie)
* [technologische Singularität](https://de.wikipedia.org/wiki/Technologische_Singularit%C3%A4t)

## 3. Fragen

### 3.1 Wo kann man mit künstlicher Intelligenz Geld verdienen?

TODO..

### 3.2 Rationale Entscheidungen vs. intuitive Denkweise: Kann man Maschinen Intuition beibringen?

Quelle: [Komplexe Entscheidungssituationen: Intuitiv beurteilen, rational begründen](https://www.wissensdialoge.de/komplexe-entscheidungssituationen-intuition)

**Rationales Entscheiden (eher Maschinen-typisch):** bewusst/schlussfolgernd, affektfrei, verbal, analytisch/zerteilend, „aktives“ Denken, wird als kontrollierbar erlebt

**Intuitives Denken (eher Mensch-typisch):** automatisch/unbewusst, emotionsbasiert, nonverbal, ganzheitlich, „passive“, spontane Gedanken/Eingebungen

Erfolgreiche KI-Systeme basieren (aktuell gesehen) auf maschinellem Lernen. Sie lernen von Daten, welche ursprünglich von Menschen (intuitiv) klassifiziert wurden. Sie handeln deshalb auf eine statistische Art und Weise von Daten, welche von Menschen ursprünglich intuitiv erzeugt wurden und "ahmen" dieses Verhalten nach. Intuition wird also in diesem Fall simuliert. Die Systeme sind jedoch genau gesehen nicht wirklich intuitiv. Die Grundlage der Entscheidung sind immer noch deterministische Algorithmen und Ablaufvorschriften. Die Klassifizierung unbekannter Objekte muss nach dem Lernprozess nicht mehr zwangsläufig "richtig" sein. Eine Kontrolle und letztendliche Entscheidung sollte (aktuell) noch immer beim Menschen bleiben. Letztendlich bleibt bei diesem Thema die Frage, ob die simulierte Intuition der Maschine für die Erreichung des gewünschten Zieles ausreicht oder eben nicht.

## 4. Verwendungszweck

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
  * Auswertung anderer Analysedaten (Maschinen, z.B. beim autonomen Fahren, etc.)
* Ermittlung der optimalsten Lösung
  * Routenplanung (kürzester Weg von A nach B)
  * Computerspiele (Computergegner, [Schach](https://blog.zeit.de/schach/als-deep-blue-das-genie-garry-kasparow-schlug/), [Brettspiel Go](https://www.welt.de/newsticker/dpa_nt/infoline_nt/brennpunkte_nt/article153220565/Google-schlaegt-Mensch-Go-Meisterspieler-entschuldigt-sich.html), etc.)
* **Kurzum:** Jede Domäne für sich ist meist sehr fortgeschritten und funktioniert auf ihrem Gebiet sehr gut (spezialisiertes Aufgabengebiet).
  
### (Noch) nicht möglich (starke künstliche Intelligenz)

* "echte" Intelligenz (starke künstliche Intelligenz)
  * *"Lieber Computer, bitte löse mein Ticket mit der Nummer xy!"*
  * *"Computer! Ich habe all meine Dokumente in der Cloud hochgeladen. Zugangsdaten findest du auf meinem USB-Stick, welchen ich dir am PC angesteckt habe. Bitte erledige nun meine Steuererklärung!"*
* **Kurzum:** [Technologische Singularität](https://de.wikipedia.org/wiki/Technologische_Singularit%C3%A4t) ist derzeit noch nicht möglich. Sprich das intelligente Verknüpfen "aller" Domänen in eine Maschine. *Wie funktioniert die Welt?*

## 5. Anwendungen

Anwendungen, welche regen Gebrauch aus dem Gebiet der künstlichen Intelligenz machen:

* [Google Translate](https://translate.google.com) (Automatische Übersetzungen)
* [DeepL](https://www.deepl.com/translator) (Übersetzungssystem auf der Basis von neuronalen Netzen)
* [Google AutoDraw](https://www.autodraw.com) (Erkennung handschriftlicher Zeichungen)
* [Microsoft Captionbot](https://www.captionbot.ai) (Automatische Bild-Objekterkennung)
* [Cloud Vision API](https://cloud.google.com/vision) (Bildanalyse)
* [Facebook FBLearner Flow](https://code.facebook.com/posts/1072626246134461/introducing-fblearner-flow-facebook-s-ai-backbone/) und FBLearner Predictor (Übersetzung Posts, Klassifizierung Fotos, Auslieferung passender Werbung)
* [IBM Watson](https://de.wikipedia.org/wiki/Watson_(K%C3%BCnstliche_Intelligenz)) (Fragenbeantwortung)
* [Apple Core ML](https://developer.apple.com/documentation/coreml) (Gesichtserkennung)
* [Amazon DSSTNE](https://github.com/amzn/amazon-dsstne) (Alexa)
* [Google Photo](https://photos.google.com) ("Smarte" Bilderkennung)

## 6. Chancen, Gefahren und Probleme der künstlichen Intelligenz

### 6.1 Chancen

* Fehlerquoten durch Unachtsamkeit werden verringert (diese Fehlerart gibt es beim Computer praktisch nicht)
  * [An den meisten Unfällen sind Menschen schuld @ DIE WELT](https://www.welt.de/sonderthemen/noahberlin/article165739463/An-den-meisten-Unfaellen-sind-Menschen-schuld.html)
* Neue Berufszweige bzw. stärkere Nachfrage schon bestehender Berufszweige
  * UIMA Modeller
  * Computer-Linguisten
  * KI-Trainer
  * Robotics Engineers
  * Data Scientists
  * etc. ..

### 6.2 Gefahren

* Arbeiten können durch Maschinen vollständig autonom übernommen werden: bestimmte Berufe werden überflüssig
  * [Droht mit Digitalisierung jedem zweiten Job das Aus? @ DIE WELT](https://www.welt.de/wirtschaft/webwelt/article150856398/Droht-mit-Digitalisierung-jedem-zweiten-Job-das-Aus.html)
  * [Diese KI könnte auch Foto-Experten den Job kosten @ mobilegeeks.com](https://www.mobilegeeks.de/news/google-creatism-diese-ki-koennte-auch-foto-experten-den-job-kosten)
* Mögliche Fehlschlüsse von Berechnungen bzw. nicht alle Berechnungen sind transparent: "Ist der Betroffene wirklich nicht kreditwürdig?"

### 6.3 Probleme

* Maschinen kennen keine Ethik. Sie muss vorher "implementiert" werden. Affekthandlungen gibt es nicht. Wie soll die Maschine bei einem unvermeidbarem Unfall reagieren? Wie ist die Schuldfrage bei Schäden bzw. Todesfällen?
  * [Der Todesalgorithmus @ ZEIT ONLINE](https://www.zeit.de/kultur/2017-09/kuenstliche-intelligenz-algorithmus-spam-autonomes-fahren)
  
## 7. Künstliche Intelligenz aus Programmierersicht

### 7.1 Am Beispiel des Machine Learnings

Bei klassischen Programmierverfahren ist die Implementierung des Modells bekannt. Das Modell hat die Aufgabe Eingaben direkt in eine Ausgabe umzuwandeln:

[![Deduktives Verfahren](/images/deduktiv.png)](/images/deduktiv.png)

Da das Modell von Anfang an bekannt ist und man die Lösung "einfach" vorhersehen kann, wird dieses Verfahren White Box Verfahren genannt. Man schließt hierbei vom Modell direkt auf die Einzelbeobachtungen (Deduktion).

Bei den Verfahren des Machine Learning wird die Vorgehensweise "umgedreht". Hierbei sind entsprechende Datensätze von Eingaben und Ausgaben bekannt (ähnlich dem Verfahren der testgetriebenen Entwicklung). Diese werden zum Lernen und Trainieren des Systems verwendet und ein mögliches Modell bestimmt. Man nennt dies auch Supervised Machine Learning:

[![Induktives Verfahren](/images/induktiv.png)](/images/induktiv.png)

Da oft nicht bekannt ist, wie das Modell entstanden ist (und es meist auch gar nicht interessiert), wird dieses Verfahren auch Black Box Verfahren genannt. Man schließt bei dieser Vorgehensweise von Einzelbeobachtungen auf das Modell und spricht bei dieser Methoden der Erkenntnisgewinnung auch von Induktion. Ein Hybrid aus beiden Varianten nennt man auch Grey Box Verfahren.

Die Methoden des Machine Learnings sind vor allem dort überaus nützlich, bei dem der Aufwand für die direkte Bestimmung des Modells unmöglich ist bzw. einen hohen Aufwand erfordert. **Beispiel:** Um ein Objekt auf einem Bild zu erkennen, wird man keinen Algorithmus direkt dafür bestimmen können, sondern auf die Methoden des Machine Learnings zurückgreifen. Entsprechende Trainingsdaten vorausgesetzt ist der Aufwand (die Kosten) für die technische Implementierung unter zuhilfenahme entsprechender technischen Ressourcen sehr viel geringer, als der Versuch das Modell direkt zu implementieren. 
  
## 8. Werkzeuge

Frameworks und Tools, welche bei dem Thema künstliche Intelligenz unterstützen bzw. Technologien der KI nutzen:

* [TensorFlow](https://www.tensorflow.org/) (Open source machine learning framework; Google)
* [Caffe](http://caffe.berkeleyvision.org) (Deep Learning Framework)
* [Keras](https://keras.io) (Python Deep Learning library)
* [Apache MXNet](https://mxnet.incubator.apache.org) (A flexible and efficient library for deep learning; Apache)
* [Apache MLlib (Spark)](https://spark.apache.org/mllib) (Scalable machine learning library; Apache)
* [Gluon](https://aws.amazon.com/de/blogs/aws/introducing-gluon-a-new-library-for-machine-learning-from-aws-and-microsoft) (Library for machine learning; Microsoft; Amazon)
* [PyTorch](https://pytorch.org) (Deep learning framework)
* [The Microsoft Cognitive Toolkit](https://www.microsoft.com/en-us/cognitive-toolkit) (Toolkit that trains deep learning algorithms; Microsoft)
* [DL4J](https://deeplearning4j.org) (Deep Learning Library for the JVM)
  
## A. Weiterführende Tutorials

* [Probleme mittels Suche lösen](https://github.com/friends-of-ai/solve-problems-by-searching)
* [Neuronale Netze erstellen](https://github.com/friends-of-ai/create-neuronal-networks)
* Coming soon..

## B. Literatur / Links

Empfohlen für den praktischen Einsatz:

* [Praxiseinstieg Deep Learning](https://www.oreilly.de/buecher/12840/9783960090540-praxiseinstieg-deep-learning.html) (Lehrbuch, Deutsch)
* [Machine Learning – kurz & gut](https://www.oreilly.de/buecher/12870/9783960090526-machine-learning-%E2%80%93-kurz-%26-gut.html) (Lehrbuch, Deutsch)
* [Neuronale Netze selbst programmieren](https://www.oreilly.de/buecher/12892/9783960090434-neuronale-netze-selbst-programmieren.html) (Lehrbuch, Deutsch)
* [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com) (Freies Online Buch, Englisch)
* [Deep Learning](http://www.deeplearningbook.org) (Ein MIT Online Buch, Englisch)
* [Ein kleiner Überblick über Neuronale Netze](http://www.dkriesel.com/science/neural_networks) (Freies eBook, Deutsch, Englisch)
* [Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning) (Liste ausgewählter Machine Learning Frameworks, Bibliotheken und Software, Englisch)
* [The most cited deep learning papers](https://github.com/terryum/awesome-deep-learning-papers) (Liste der bekanntesten Paper zum Thema Deep Learning, Englisch)
* [Cheat Sheets for AI, Neural Networks, Machine Learning, Deep Learning & Big Data](https://becominghuman.ai/cheat-sheets-for-ai-neural-networks-machine-learning-deep-learning-big-data-678c51b4b463) (Umfangreiche Liste von KI Cheat Sheets, Englisch)

## C. Quellen

* Inspiriert von der Vorlesung und der Übung "Künstliche Intelligenz" der TU-Chemnitz: [Künstliche Intelligenz](https://www.tu-chemnitz.de/informatik/KI/edu/ki)
* [Google schlägt Mensch - Go-Meisterspieler entschuldigt sich @ DIE WELT](https://www.welt.de/newsticker/dpa_nt/infoline_nt/brennpunkte_nt/article153220565/Google-schlaegt-Mensch-Go-Meisterspieler-entschuldigt-sich.html)
* [Als Deep Blue das Genie Garri Kasparow schlug @ ZEIT ONLINE](https://blog.zeit.de/schach/als-deep-blue-das-genie-garry-kasparow-schlug)
* [Computer und Roboter - Künstliche Intelligenz @ Planet Wissen](https://www.planet-wissen.de/technik/computer_und_roboter/kuenstliche_intelligenz)

## D. Authors

* Björn Hempel <bjoern@hempel.li> - _Initial work_ - [https://github.com/bjoern-hempel](https://github.com/bjoern-hempel)

## E. License

This tutorial is licensed under the MIT License - see the [LICENSE.md](/LICENSE.md) file for details
