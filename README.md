# Alpaka Bingo

Eine kleine Webseite die ein Bingo Feld in HTML5 & JS implementiert.


Wenn das Mittelfeld nicht editierbar sein soll, oder das Wort angepasst werden soll muss in dies in `script.js` geschehen.

`contentEditable='true'` ist das Attribut was entfernt werden muss, damit das Feld nicht mehr editierbar ist.


Um ein weiteres Board hinzuzufügen, kopiere die `exampleboard.html` & `exampleboard.js` und passe sie nach deinen Wünschen an. Danach stelle einen PR.

** Du brauchst mindestens 24 Wörter damit das Board rendered! Nach oben gibt es quasi keine Limits! **

Nach dem mergen ist das Board unter https://bingo.alpaka.live/boardname.html aufrufbar.

Wenn du das Board direkt beim Aufruf sichtbar haben möchtest, ändere in `index.html` in der Zeile `<meta http-equiv="refresh" content="0; URL='/wasisteinehackerin.html'" /> ` das `URL='wasisteinehackerin.html'` in den Link auf deine Seite und packe das mit in den MR.

Merge Requests für hübscheres Design sind willkommen! <3

(Da der Code zu großen Teilen zusammen geklaut ist, keine Lizenz. Es gelten nur die Lizenzen die im Code sind.)

kthxbye