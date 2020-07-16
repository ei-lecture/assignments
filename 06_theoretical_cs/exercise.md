# 6. Formale Sprachen und Automaten - Übungen


## 6.1 Parkscheinautomat
Auf einem Parkplatz kostet das Parken 1,50 Euro. Ein Parkscheinautomat akzeptiert 50 Cent, 1 Euro und 2 Euro-Münzen. Nach Einwurf der korrekten Geldsumme liefert er das Ticket und gegebenenfalls das Restgeld. Er besitzt keine Abbruchtaste.

Entwickeln Sie einen Automaten (DEA), der den Parkscheinautomaten realisiert, alle korrekten Geldbeträge akzeptiert und das richtige Restgeld zurückgibt. Geben Sie den Automaten als Diagramm an, eine Tabelle ist nicht nötig.


## 6.2 Regulärer Ausdruck für Matrikelnummern
Geben Sie einen regulären Ausdruck an, der die Matrikelnummern der Studierenden, die im Sommersemester 2018 angefangen haben (beginnen mit `181` und darauf folgen immer vier Ziffern) matched.

Erweitern Sie den regulären Ausdruck danach auf das Wintersemester 2017. Beachten Sie, dass die Matrikelnummern im Wintersemester mit `172` *und* `173` beginnen können.

Testen Sie Ihren Ausdruck mit verschiedenen Matrikelnummern.


## 6.3 Ersetzen mit einem regulären Ausdruck
Geben Sie einen regulären Ausdruck an, der alle Vorkommen von "t" in einem Text durch "7" ersetzt. Orientieren Sie sich an der Syntax des Unix-Werkzeugs `sed` bei der Angabe des Ausdrucks (extended regular expressions mit der `-E`-Option).


## 6.4 Wörter tauschen
Geben Sie einen regulären Ausdruck an, der zwei durch Bindestrich (`-`) verbundene Wörter vertauscht. Z.B. soll aus "Speicher-Fehler" das Wort "Fehler-Speicher" werden. Orientieren Sie sich an der Syntax des Unix-Werkzeugs `sed` bei der Angabe des Ausdrucks (extended regular expressions mit der `-E`-Option). Testen Sie den Ausdruck mit Hilfe von `sed`.


## 6.5 Greedy Match
Was ist damit gemeint, wenn man bei regulären Ausdrücken von einem sogenannten "greedy match" spricht? Geben Sie ein Beispiel an.


## 6.6 Backus-Naur-Form (BNF)
In C müssen Variablennamen nach der folgenden Regel gebildet werden: "Namen bestehen aus Buchstaben und Ziffern; dabei muss das erste Zeichen ein Buchstabe sein. Der Unterstrich zählt als Buchstabe."

Beschreiben Sie diese Regel mit einem Ausdruck in Backus-Naur-Form.

## 6.7 Erweiterte Backus-Naur-Form (EBNF)
Gegeben sei die folgende Grammatik in EBNF-Form

```console
expression = term  { ("+" | "-") term };
term       = factor  { ("*" | "/") factor };
factor     = constant | variable | "(" expression ")";
variable   = "x" | "y" | "z";
constant   = digit {digit} ;
digit      = "0" | "1" ... "9";
```

Geben Sie mindestens vier beispielhafte Ausdrücke an, die von dieser Grammatik beschrieben werden.


## 6.8 50 Affen
Zur Illustration der zeitlichen Komplexität führen Sie folgende Betrachtung durch: Wie wahrscheinlich ist es, dass 50 Affen an 50 Schreibmaschinen in 50 Jahren irgendwann auch die erste Seite von Shakespeares Drama "Hamlet" getippt haben würden (Groß- und Kleinschreibung wird ignoriert)? Machen Sie hierzu plausible Annahmen bzgl. der Zeichenzahl pro Seite und die Anzahl der Anschläge pro Sekunde.


## 6.9 Komplexität und Verständlichkeit
Wenn die Komplexität eines Algorithmus X größer als die eines Algorithmus Y ist, bedeutet dies, dass X schwerer zu verstehen ist als Y? Erläutern Sie Ihre Antwort.


## 6.10 Komplexität bestimmen
Gegeben seien die folgenden Programmfragmente. Geben Sie die jeweilige Ausführungszeit an. Geben Sie den Aufwand mittels der O-Notation an. Sie dürfen davon ausgehen, dass der fehlende Schleifenrumpf eine konstante Ausführungszeit hat.

Fall 1:
```java
for (int i = 0; i < n; i++) {
    // Rumpf
}
```

Fall 2:
```java
for (int i = 0; i < n; i++) {
    // Rumpf
}

for (int k = 0; k < n; k++) {
    // Rumpf
}
```

Fall 3:
```java
for (int i = 0; i < n; i++) {
    for (int j = 0; j < n; j++) {
      // Rumpf
    }
}
```

Fall 4:
```java
for (int i = 0; i < n; i++) {
    for (int j = 0; j < i; j++) {
        // Rumpf
    }
}
```

Fall 5:
```java
for (int i = 0; i < n; i++) {
    for (int j = 0; j < n; j++) {
        for (int k = 0; k < n; k++) {
           // Rumpf  
        }        
    }
}
```


## 6.11 Komplexität berechnen
Betrachten Sie folgende Messdaten, die für die Laufzeit eines Programms bei unterschiedlichen Datenmengen (n) ermittelt wurden:

  1. n^3 + 4n^2 + 2n + 12
  2. 2n(8 + log(n))
  3. (8n + 12) / 6
  4. 1 + 2 + 3 + 4 + ... + n
  5. 7 + log(n^3)
  6. 8n + log(n)

Geben Sie den Aufwand mittels der O-Notation an.


