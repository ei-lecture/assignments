# 10. IT-Sicherheit - Übungen

## 10.1 Begriffe der IT-Sicherheit
Erläutern Sie die folgenden Begriffe:

  1. Vertraulichkeit
  2. Integrität
  3. Verfügbarkeit


## 10.2 Angriffswerkzeuge
Erläutern Sie die folgenden Begriffe: 

  1. Trojaner, Trojanisches Pferd
  2. Malware
  3. Virus 
  4. Rootkit
  5. Exploit
  6. Zero-day Exploit 


## 10.3 Überwachungsfreiheit
Heutzutage wird man zunehmend von privaten Anbietern überwacht - und weniger von Staaten (oder...?). Wie soll man sich verhalten, wenn man der Überwachung weitestgehend entgehen will? 


## 10.4 Sicherheit beim Surfen
  1. Was sind Cookies und sind diese gefährlich?
  2. Welche Einstellungen in meinem Browser sollte ich vornehmen? 
  3. Was sollte ich beim Surfen beachten? 


## 10.5 Kryptographische Verschlüsselung
Was ist der Unterschied zwischen symmetrischer und asymmetrischer Verschlüsselung, und wofür werden diese jeweils im Internet eingesetzt? Geben Sie jeweils 2 Beispiele für Verfahren. 


## 10.6 Digitale Signatur
Beschreiben Sie drei Einsatzgebiete der Technologie der "Digitalen Signatur" (im kryptographischen Sinn). 


## 10.7 Forward Secrecy
Warum ist es wichtig, dass Webseiten-Betreiber ihre Server so konfigurieren, dass bei TLS die sogenannte __Forward Secrecy__ gewährleistet ist?


## 10.8 Authentifizierungsverfahren
Benennen Sie drei verschiedene Authentifizierungsverfahren und jeweils deren primäre Schwäche. 


## 10.9 Garagentoröffner
Viele Garagentore können per Funksender geöffnet werden. Warum reicht es nicht, die Kommunikation zwischen dem Sender und Empfänger aufzuzeichnen, um das Tor später noch einmal zu öffnen?


## 10.10 Probleme von Keyless-Entry-Systemen
Man hört und [sieht](https://youtu.be/odG2GX4_cUQ) häufiger, dass Autos mit Keyless-Entry-Systemen gestohlen werden. Die Schlüssel setzen allerdings ein Challenge-Response-Verfahren ein, das als sicher gilt. Wie gelingt des den Tätern trotzdem das Fahrzeug zu stehlen und welche Schwachstelle nutzen sie aus?


## 10.11 Sichere Passwörter
Angenommen ein Passwort besteht aus acht Zeichen aus dem Alphabet A-Z (26 Zeichen) und die Überprüfung des Passwortes dauert eine Millisekunde.

  1. Wie lange dauert es, alle möglichen Passwörter durchzuprobieren?
  2. Erweitern Sie die möglichen Zeichen (bei gleicher Passwortlänge) noch um die Zahlen 0-9: Wie lange dauert es jetzt?
  3. Erweitern Sie die Passwortlänge um eins (ohne die Zahlen 0-9): wie lange dauert es jetzt?
  4. Was ist besser? Mehr unterschiedliche Zeichen, oder längere Passwörter?
  5. Wie lange brauchen moderne Prozessoren, um ein Passwort zu testen?


## 10.12 Speicherung von Passwörtern
Grundsätzlich sollte man als Programmierer keine Sicherheitsfunktionen selbst implementieren, sondern immer vorhandene und gut getestete Bibliotheken verwenden.

Trotzdem angenommen, Sie wollten ein Passwort sicher speichern und verarbeiten, wie gehen Sie vor?

Ihre Antwort sollte die Folgenden Begriffe berücksichtigen:

  1. Rainbow Table
  2. Salt
  3. Brute-Force-Angriff
  4. Round (Runden)
  5. Hash-Algorithmen
  6. Klartext-Passwort


## 10.13 Hashen von Telefonnummern
In einem Softwareprojekt soll das Verhalten von deutschen Telefonkunden _anonym_ ausgewertet werden. Der Projektleiter schlägt vor, dass die Telefonnummern als Hashwert (MD5) gespeichert werden soll und behauptet, dass so keinerlei Rückschluss auf die ursprüngliche Nummer möglich ist. Wie bewerten Sie diese Aussage? Begründen Sie Ihre Antwort ausführlich!


