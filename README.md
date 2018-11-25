# Rabbio 

von Janina Gräfnitz und Carolin Oelschlägel, Klasse 12a

## Inhaltsverzeichnis
* [Projektvorstellung](#Projektvorstellung)
  * [Die Intention des Spiels](#Dieintentiondesspiels)
* [Das Spiel selber programmieren](#dssp)
  * [MIT App Inventor](#Aufbau)
  * [Erste Schritte](#ErsteSchritte)
  * [Das Hasen-Spiel](#DasHasenSpiel)

## Projektvorstellung

Unser Projekt ist ein Spiel namens "Rabbio" und wurde  mit "MIT App Inventor" programmiert. Das Grundprinzip dieses Spiels ist es, mit einem Hasen vertikal durch verschieden schnelle Kugeln hindurch zu steuern, um eine Möhre am oberen Bildschirmrand zu erreichen. Sobald der Hase die Möhre berührt, erscheint je nach Level eine unterschiedlich schwere Frage zum Fachbereich Biologie. Nur wenn man die Frage richtig beantwortet, gelangt man zum nächsten Level, bis man letztendlich alle drei Level durchgespielt hat und man damit gewonnen hat.

 ![bsp Bildschirmfoto 2018-11-24 um 13.16.24].png)

## Die Intention des Spiels

Mit dem Spiel "Rabbio" sollen Spaß beim Spielen und das Erweitern des Wissens in dem Fach Biologie miteinender vereint werden. Das Spiel soll somit zum Lernen motivieren. Da dieses mit dem Spiel verbunden ist, erscheint es für den Spieler als eine positive Erfahrung. Kognitive und geistige Fähigkeiten des Spielers werden miteinander vereint.
Der Name "Rabbio" setzt sich aus den englischen Wörtern "rabbit" und "biology" zusammen. 

## Das Spiel selber programmieren

### MIT App Inventor

Um das Spiel selber zu programmieren zu können, sollte man sich zunächst mit dem Programm "MIT App Inventor" vertraut machen.
MIT App Inventor ist ein seit 2010 veröffentliches Programm zum Programmieren in Blocksprache. 
Mit dem Programm kann man Apps für Smartphones und Tablets programmierern, welche mit Android Betriebssystem laufen. Für den Beginn des Jahres 2019 ist geplant, dass die mit MIT App Inventor programmierten Apps auch mit dem Apple Betriebssystem iOS funktionierern.
MIT App Inventor ist online frei zugänglich, vor der ersten Anwendung muss man sich mit seinem Google Konto registrieren.
Danach kann man begonnene Prokjekte online speichern, sodass man jederzeit darauf zugreifen kann und diese weiterbearbeiten kann.
Das Programm funktioniert auf Englisch und 11 weiteren Sprachen, zu denen Deutsch leider nicht gehört. 

MIT App Inventor teilt sich in zwei Ebenen auf, den Design Editor und den Block Editor. 

In dem Design Editor kann man Hintergründe und ImageSprites erstellen. 
Dazu kann man Bilder von seinem eigenen Computer oder aus dem Internet in das Prokekt hochladen. Besonders an MIT App Inventor ist, dass man mehrere verschiedene Screens designen kann. Dies eignet sich gerade für Spiele wie Rabbio sehr gut, da dieses aus verschiedenen Teilen (dem Hasenspiel und dem Quizteil) besteht, wofür ein komplett verschiedenes Design des Bildschirms nötig ist. 
In die verschieden Screens kann man im Design Editor verschiedene Buttons und Labels mit Text hinzufügen.
Desweiteren kann man dort Bälle erstellen, diese kommen auch in unserem Spiel vor. Der wesentliche Unterschied zwischen ImageSprites und Bällen ist der, dass die Bälle sehr simpel aufgebaut sind. An ihnen kann man lediglich die Geschwindigket, Größe u. Ä. ändern. Die ImageSprites können durch Bilddateien individuell gestaltet werden.

In dem Block Editor kann man per Drag and Drop verschiedene Blocks auf eine Fläche ziehen. 
Diese kann man beliebig miteinander kombinieren und bei einigen Blocks selber bestimmte Dinge dazutragen. 
Man kann verschiede Screens miteinander verknüpfen, die Fortbewegung der ImageSprites und die Bälle programmieren und entscheiden, was bei dem Berühren bestimmter anderer ImageSprites oder dem Antippen verschiedener Buttons passiert. 

### Erste Schritte

Zunächst muss man ein neues Projekt auf MIT App Inventor erstellen.
Man sollte sich bestenfalls bereits vorher ein Konzept gemacht haben, wie das Spiel aufgebaut sein soll.
Dann beginnt man mit dem ersten Screen, dieser wird erstellt. Da man die Screens im Nachhinein nicht umbenennen kann, empfiehlt sich direkt verständliche Namen zu verwenden, die das Arbeiten später erleichtern. 
Screens 1, welcher direkt zu Beginn erstellt wird, ist immer der Startscren des Spiels, er öffnet sich direkt, wenn man die App auf dem Smartphone startet. 

Deshalb empfiehlt sich für Screen 1 ein Label mit dem Spielnamen zu erstellen (hier: Rabbio oder auch einfacher "Startscreen"), außerdem einen passenden Hintergrund zu wählen (hier: die Spielfarbe grün), eine kurze Spielanleitung einzufügen und gegebenenfalls ein ansprechendes Bild (hier: von der Spielfigur, dem Hasen).
Desweiteren musss ein Button per Drag and Drop eingefügt werden, der später zum Starten des Spiels dienen soll. 
Dies alles geschieht in der Ebene "Design Editor".

Anschließend wechselt man in den "Block Editor" 
Dort werden die entsprechenden Blocks eingefügt, sodass sich beim Klicken des Button ein neuer Screen öffnet (das das erste Level des Hasenspiels).

### Das Hasen-Spiel

Bei dem Hasenspiel-Screen muss ebenfalls zunächst der Bildschirm designt werden. 
Wichtig ist, dass man einen sogenannten "Canvas" in den Hintergrund ziehen muss. Er füllt diesen komplett aus, nur auf dem Canvas können sich hinterhger Bälle und Sprites bewegen. 



