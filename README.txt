ZÄHLWERK – Anleitung zum Veröffentlichen mit GitHub Pages
=========================================================

Inhalt dieses Ordners
  index.html              die App
  manifest.webmanifest    Name, Farben und Icons für die Installation
  sw.js                   Offline-Betrieb
  icons/                  App-Icons

So kommt die App auf dein iPhone (einmalig, am PC, ca. 10 Minuten)

 1. Auf github.com anmelden und oben rechts über "+" ein neues Repository anlegen.
    Name:  zaehlwerk      (ohne Umlaut, alles klein)
    Sichtbarkeit: Public  (für kostenloses GitHub Pages nötig)
    Der Code ist dann öffentlich lesbar. Deine Messdaten bleiben auf deinen Geräten
    und liegen nie im Repository.

 2. Im neuen Repository auf "uploading an existing file" klicken.
    Den entpackten Inhalt dieses Ordners hineinziehen: die Dateien index.html,
    manifest.webmanifest, sw.js UND den ganzen Ordner "icons".
    Unten auf "Commit changes" klicken.

 3. Oben auf "Settings", links auf "Pages".
    Bei "Source" die Option "Deploy from a branch" wählen, Branch "main" und
    Ordner "/ (root)", dann "Save".

 4. Nach ein bis zwei Minuten steht dort die Adresse, in der Regel
    https://DEIN-BENUTZERNAME.github.io/zaehlwerk/

 5. Auf dem iPhone die Adresse in Safari öffnen, auf das Teilen-Symbol tippen und
    "Zum Home-Bildschirm" wählen. Ab jetzt startet Zählwerk wie eine App und
    funktioniert auch ohne Internet.

Updates
  Neue Dateien im Repository hochladen (gleiche Namen überschreiben die alten).
  Die App holt sich die neue Version beim nächsten Start mit Internet von selbst.

Wichtig
  - Die Daten liegen nur im Speicher des jeweiligen Geräts. Unter
    Einstellungen > "Sicherung speichern" eine Datei erzeugen und gut aufheben.
  - Die Testversion in Claude und die Version auf GitHub haben getrennte Daten.
