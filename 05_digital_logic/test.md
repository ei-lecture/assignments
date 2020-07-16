# 5. Digitale Logik - Test (100 Punkte)

Hinweis: Die Aufgaben verwenden der Einfachheit halber die Symbole aus Java für die Darstellung der

  * _Konjunktion_ (AND): `&`,
  * _Disjunktion_ (OR): `|` und
  * _Negation_ (NOT): `!`

## 5.1 Leistung eines Wasserkochers (10 Punkte)
Auf einem Wasserkocher steht 230V, 5A. Welche elektrische Leistung nimmt das Gerät auf? (Geben Sie auch den Rechenweg an.)


## 5.2 Logische Funktionen auf Bitfolgen anwenden (15 Punkte)
Berechnen Sie `(10010100 & !00101111)`:


## 5.3 Bits maskieren (20 Punkte)
Angenommen, sie wollen in beliebigen Bitfolgen (8 Bit) die letzten beiden Bits immer auf Eins setzen und die erste zwei Bit umdrehen (0 -> 1, 1 -> 0), also z.B. aus `10101001` soll `01101011` werden. Wie können Sie dies mit entsprechenden booleschen Operatoren erreichen?


## 5.4 Ausdruck in Wahrheitstabelle darstellen (20 Punkte)
Stellen Sie eine Wahrheitstabelle für folgenden Ausdruck auf (P und Q sind Aussagen, die Wahr T oder Falsch F sein können): `(P & !Q) | (!P & !Q)`


## 5.5 Disjunktive Normalform (35 Punkte)
Eine Schaltfunktion y mit drei Eingängen x1, x2, x3 sei durch folgende Funktionstabelle gegeben:

| x1  | x2  |  x3 | f  |
|-----|-----|-----|----|
|  0  |   0 |   0 |  1 |
|  0  |   0 |   1 |  0 |
|  0  |   1 |   0 |  1 |
|  0  |   1 |   1 |  0 |
|  1  |   0 |   0 |  1 |
|  1  |   0 |   1 |  0 |
|  1  |   1 |   0 |  1 |
|  1  |   1 |   1 |  0 |

Geben Sie die Schaltfunktion in disjunktiver Normalform an und erstellen Sie das dazugehörige KV-Diagramm. Welche optimierte Funktion ergibt sich?

<img src="img/kv-leer.png" width="200">


