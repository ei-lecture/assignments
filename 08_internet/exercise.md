# 8. WWW und Internet - Übungen

## 8.1 C/S-Modell vs. P2P
Vergleichen Sie Client/Server-Modell mit dem Peer-to-Peer-Modell. Geben Sie Beispiele für die beiden Modelle.


## 8.2 Namensauflösung
Sie finden folgenden Eintrag in der Datei `/etc/hosts` auf Ihrem Rechner (bzw. `C:\Windows\System32` `\Drivers\etc\hosts`, falls Sie Windows verwenden sollten):

```console
127.0.0.1  localhost
127.0.0.1  www.google.de
```

Was passiert, wenn Sie im Browser die URL `http://www.google.de` eingeben (welche Anzeige sehen Sie und warum)?


## 8.3 DNS
Wie funktioniert die Auflösung einer Adresse (z.B. `www.google.com`) in die IP-Adresse? Wo kommt das DNS ins Spiel?

Bitte beschreiben Sie den Ablauf Schritt für Schritt.


## 8.4 Mail-Protokolle
Wieso gibt es für den Umgang mit E-Mails drei Protokoll (SMTP, POP3, IMAP)?


## 8.5 HTTPS
Was ist der Unterschied zwischen dem Zugriff auf die URL `http://stargazer.universe.org` und `https://stargazer.universe.org`?


## 8.6 HTML-Struktur
Öffnen Sie eine Webseite und schauen Sie sich den Quelltext der HTML-Datei an. Welche grundlegende Struktur können Sie erkennen?


## 8.7 SSL-Stripping
Beschreiben Sie bitte kurz und knapp, was man unter einem __SSL-Stripping__-Angriff versteht.


## 8.8 HTML-Seite erstellen
Erstellen Sie eine einfache HTML-Seite, in der Sie Ihren Lieblingsfilm vorstellen. Verwenden Sie auf jeden Fall Bilder, um die Seite ansprechender zu gestalten. Verwenden Sie CSS, um die Seite optisch zu gestalten.

Legen Sie die Seite auf dem Rechner `agent-smith.informatik.hs-mannheim.de` im Verzeichnis `public_html` (falls nicht vorhanden, müssen Sie das Verzeichnis anlegen) unter dem Namen `index.html` ab. Bilder und weitere Dateien müssen Sie ebenfalls in das `public_html`-Verzeichnis legen. Sie können die Seite dann unter `http://agent-smith.informatik.hs-mannheim.de/~NUTZERNAME/` aus dem Netz der Hochschule erreichen, wobei NUTZERNAME Ihr Nutzername auf dem Rechner ist, z.B. `f.meier`.

Sollte es beim Zugriff auf die Seite eine Fehlermeldung im Browser geben ("Permission denied"), überprüfen Sie bitte, ob Ihr Homeverzeichnis für alle die x-Berechtigung hat und das Verzeichnis `public_html` für alle r- und x-Berechtigungen hat. Falls nicht, ändern Sie die Berechtigungen mit `chmod a+x ~` und `chmod a+rx ~/public_html`.

Abgabe: URL der Seite


