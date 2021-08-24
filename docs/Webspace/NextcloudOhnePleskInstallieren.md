---
id: NextcloudOhnePleskInstallieren
title: Nextcloud ohne Plesk One-Click Installer installieren
---

> Schritt 1: Installer Herunterladen

Lade dir den aktuellen Nextcloud-Installer [hier](https://download.nextcloud.com/server/installer/setup-nextcloud.php) herunter

> Schritt 2: Installer speichern

Lade die Datei auf den Speicher deiner Domain hoch
![](https://screen.r-it.link/Zono0/QoWaQIfE89.png/raw)

> Schritt 3: Einrichtung

Rufe nun die Datei übr den Webbrowser aus. Gehe hierzu auf ```DeineDomain/setup-next-cloud.php```

> Schritt 3.1: Installation

Wähle das Verzeichniss aus, indem deine Cloud erreichbar sein soll. Soll Die Cloud direkt im Basisverzeichniss installiert werden, gebe hier `.` ein. Ansonsten das Unterverzeichniss, wie z.B. `cloud`
![](https://screen.r-it.link/Zono0/PILoqUmu72.png/raw)
Klicke danach auf "Next"</br>
Die nun folgende Installation kann einige Momente dauern. Habe hier einfach ein wenig geduld!

> Schritt 3.2: Setup

Lege dir dort nun einen Admin-Account an. Gebe dafür einen Nutzernamen sowie ein Passwort an.
![](https://screen.r-it.link/Zono0/JOpaROQO34.png/raw)
Danach wird eine MySQL-Datenbank benötogt. Diese erstellen wir uns in Plesk: </br>
![](https://screen.r-it.link/Zono0/pemUjiwe64.png/raw)
![](https://screen.r-it.link/Zono0/fArEpULi51.png/raw)
Hier Geben wir einen Datenbank-Namen an. Danach musst du deine Domain auswählen, auf der Du deine Nextloud installiert hast. </br>
Danach suchst Du dir einen Datenbank-User-Namen und gibst diesen hier ein. Anschließend wird noch ein Passwort für die Dantenbanke benötigt. Hier kannst du dir entweder eines aussuchen und 2 mal eingeben, oder du klickst auf generieren um dir eines erstellen zu lassen.</br>
Mit einem Klick auf "Anzeigen" wird dir das Passwort im oberen Textfeld eingeblendet, sodass du es dir kopieren kannst.</br>
Dieses solltest du nun in dem Einrichtungsassistenten deiner NextCloud eingeben. Danach sollte es so aussehen:
![](https://screen.r-it.link/Zono0/QOzoSuLa86.png/raw)
Nun kannst du noch mit einem Häkchen auswählen, ob empfohlene Apps für deine Nextcloud mitinstalliert werden sollen. </br>
Das hängt davon ab, ob du die Cloud ausschließlich als Datenablage nutzen willst oder auch als eine Art "Büro" </br>
Wenn du sie nur als Datenablage nutzen willst, brauchst Du diese Apps nicht. Man kann sie aber jederzeit Nachträglich installieren.</br>
Nun kannst Du auf "Installation abschließen" drücken. Dieser Vorgang kann wieder ein paar Minuten daurn.

> Fertig!

Du solltest nun auf deine Nextcloud weitergeleitet werden!