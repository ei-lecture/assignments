# Erstellen der Lösungen mit LaTeX

## Werkzeuge

Sie können entweder die Datei lokal auf Ihrem Rechner kompilieren oder Sie nutzen den Online-Dienst [Overleaf](https://www.overleaf.com).

### Lokales Erzeugen

Sie müssen LaTeX auf Ihrem Rechner installieren. Bei Linux erfolgt dies einfach über den Paketmanager der verwendeten Distribution, z.B. `sudo apt install texlive-full` für Ubuntu. Für Windows und MacOS empfehlen sich:

  * [MikTeX](http://miktex.org/) für Windows
  * [MacTeX](http://tug.org/mactex/) für MacOS

Zum Editieren der Datei verwenden Sie entweder einen normalen Texteditor (z.B. Visual Studio Code) oder eine integrierte Entwicklungsumgebung. Hierbei haben sich folgende bewährt:

  * [TeXnicenter](http://www.texniccenter.org/) für Windows (siehe unten)
  * [Texmaker](http://www.xm1math.net/texmaker/) für Windows, MacOS und Linux

Achten Sie darauf, die Dokumente im UTF-8-Format abzulegen. Nur so ist eine plattformunabhängige Verwendung gewährleistet. Die Vorlagen hier sind ebenfalls im UTF-8-Format.

### Overleaf

 * Laden Sie die ZIP-Version der Vorlage [hier](https://github.com/ei-lecture/assignments/raw/master/loesung_template.zip) herunter.
 * Melden Sie sich bei [Overleaf](https://www.overleaf.com) an und loggen Sie sich ein.
 * Gehen Sie auf "New Project" und wählen Sie "Upload Project"
 * Laden Sie die ZIP-Datei hoch.
 * Sie können das Dokument jetzt in Overleaf editieren und das PDF erzeugen.


## Benutzung des Templates

Wie eine fertige Lösung aussehen kann sehen Sie am [Beispiel](01_intro/loesung.pdf) und dem dazugehörigen [Quelltext](01_intro/loesung.tex). Denken Sie daran, Ihren Namen und Ihre Matrikelnummer im `\author`-Tag anzugeben und das Kapitel und seinen Namen über `\kapitel` und `\kapitelname` zu setzen.

Die Lösungen zu den Aufgaben tragen Sie dann in die entsprechenden `\subsection`-Abschnitte ein.

Wenn Sie eine Einführung zu LaTeX suchen, bieten sich die [Seiten der TU Graz](https://latex.tugraz.at/latex/tutorial) an. Zu speziellen Fragen findet man auf [Stackexchange](https://tex.stackexchange.com/) oft schnell eine Antwort.
