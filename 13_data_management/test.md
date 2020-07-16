# 13. Datenmanagement - Test (100 Punkte)

## 13.1 Datenbank verstehen (15 Punkte)
Gegeben sei das folgende Datenbankschema. Bitte geben Sie alle Stücke von John Cage an.

_KOMPONIST_

| ID | Nachname  | Vorname    | geboren    | gestorben  |
|----|-----------|------------|------------|------------|
|  1 | Bach      | Johann     | 1685-03-31 | 1750-07-28 |
|  2 | Cage      | John       | 1912-09-05 | 1992-08-12 |
|  3 | Riehm     | Rolf       | 1937-06-15 | NULL       |

_WERK_

| ID | Komponist | Titel                |
|----|-----------|----------------------|
|  1 |         1 | Magnificat           |
|  2 |         1 | Triosonaten          |
|  3 |         1 | Englische Suiten     |
|  4 |         2 | Imaginary Landscapes |
|  5 |         2 | 4:33                 |
|  6 |         3 | Abrazzo-Oper         |
|  7 |         3 | Gewidment            |


## 13.2 Relation (70 Punkte)
Geben Sie ein Datenbankschema an, das die Beziehung zwischen Dirigenten und den aufgeführten Stücken abbildet. Beachten Sie, dass ein Stück von mehreren Dirigenten aufgeführt werden kann und dass ein Dirigent unterschiedliche Stücke aufführt.

Fügen Sie in Ihr Schema einige Beispieldaten ein.


## 13.3 Integration über die Datenbank (15 Punkte)
Warum ist es keine gute Idee, dass mehrere Anwendungen Daten über ein gemeinsames DBMS austauschen?


