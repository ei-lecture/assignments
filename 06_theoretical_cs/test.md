# 6. Formale Sprachen und Automaten - Test (100 Punkte)

## 6.1 DEA (20 Punkte)
Entwerfen Sie einen Automaten (DEA), der eine Sprache akzeptiert, die aus den beiden Wörtern `abba` und `aba` besteht. Geben Sie den Automaten als Diagramm an, eine Tabelle ist nicht nötig.


## 6.2 Regulärer Ausdruck für Jahreszahlen (10 Punkte)
Geben Sie einen regulären Ausdruck an, der alle Jahreszahlen von 2000-2999 matched aber keine anderen Zahlen, z.B. `20` oder `22000`.


## 6.3 Wörter tauschen (10 Punkte)
Geben Sie einen regulären Ausdruck an, der zwei durch Bindestrich (`-`) verbundene Wörter vertauscht. Z.B. soll aus "Speicher-Fehler" das Wort "Fehler-Speicher" werden. Orientieren Sie sich an der Syntax des Unix-Werkzeugs `sed` bei der Angabe des Ausdrucks (extended regular expressions mit der `-E`-Option).

Kreuzen Sie die richtige Antwort an.

  * [ ] `sed -E 's/.+-.+/\2-\1/g'`
  * [ ] `sed -E 's/(*)-(*)/$2-$1/g'`
  * [ ] `sed -E 's/.+-.+/$2-$1/g'`
  * [ ] `sed -E 's/[.+]-[.+]/\2-\1/g'`
  * [ ] `sed -E 's/(.+)-(.+)/$2-$1/g'`
  * [ ] `sed -E 's/(*)-(*)/\2-\1/g'`
  * [ ] `sed -E 's/[.+]-[.+]/$2-$1/g'`
  * [ ] `sed -E 's/(.+)-(.+)/\2-\1/g'`

## 6.4 Erweiterte Backus-Naur-Form (EBNF) (25 Punkte)
Gegeben sei die folgende Grammatik in EBNF-Form

```console
sign       = "+" | "-"
even-digit = "0" | "2" | "4" | "6" | "8"
digit      = even-digit | "1" | "3" | "5" | "7" | "9"
number     = [sign]{digit}even-digit
```

Geben Sie mindestens vier beispielhafte Ausdrücke an, die von dieser Grammatik beschrieben werden. Welche Art von Ausdrücken beschreibt diese EBNF?


## 6.5 Komplexität bestimmen (15 Punkte)
Gegeben sei das folgenden Programmfragment. Geben Sie die Ausführungszeit und den Aufwand mittels der O-Notation an. Sie dürfen davon ausgehen, dass der fehlende Schleifenrumpf eine konstante Ausführungszeit hat.

```java
for (int i = 0; i < n; i++) {
    for (int j = 0; j < n; j++) {
      // Rumpf
    }
}

for (int k = 0; k < n; k++) {
    // Rumpf
}
```


## 6.6 Komplexität berechnen (20 Punkte)
Betrachten Sie folgende Messdaten, die für die Laufzeit eines Programms bei unterschiedlichen Datenmengen (n) ermittelt wurden:

  1. n^4 + 4n^3 + 2n^2 + 12
  2. n(7 + log(n))
  3. 7 + log(n^4)

Geben Sie den Aufwand mittels der O-Notation an.


