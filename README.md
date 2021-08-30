# GHC Control Docker

## Node.js Installation auf Windows

Zuerst muss Node.js auf dem PC installiert werden.

Die Website zum runterladen ist:
**https://nodejs.org/en/download/** oder klicken Sie [hier](https://nodejs.org/en/download/) um direkt auf die Website geleitet zu werden.

- Klicken Sie auf der Website auf den linke Knopf, wie im folgenden Bild markiert, um Node.js herunterzuladen.

![NodejsWebsite](img/nodejs.png?raw=true)

- Öffnen Sie die heruntegeladene Datei mit einem Doppelklick.

Sie finden die Installationsdatei im Windows Explorer unter Downloads wie im folgenden Bild.

![NodeJSInstallation](img/node_down.png?raw=true)

- Folgen Sie nun den Anweisungen des geöffneten Installationsfensters von Node.js. Drücken Sie immer einfach **Next** und stimmen Sie den
AGB zu, bis zu **Install** am Ende gelangen.

- Nun wird Node.js installiert, dies kann ein paar Minuten dauern. Am Ende klicken Sie auf **Finish** wie im folgenden Bild gezeigt. Danach ist die Installation zu Node.js abgeschlossen.

![NodeJSInstallFinish](img/nodejs_finish.png?raw=true)

## Yarn Installation

Als zweites muss ein Tool namens **Yarn** installiert werden.

- Um dies zu tun drücken Sie bitte **STRG + R** gleichzeitig.

- Es öffnet sich ein Fenster links unten am Bildschirm, geben Sie hier den Text `cmd`ein und drücken Sie dann **Enter**:

![NodeJSInstallation](img/cmd.png?raw=true)

- Es öffnet sich ein Fenster. Hier tippen Sie den Befehl `npm install --global yarn` ein und drücken dann **Enter**.

- Das Programm wird nun installiert, wenn es richtig installiert worden ist, sieht es folgerndermaßen aus:

![NodeJSInstallation](img/yarn.png?raw=true)

## Docker Installation auf Windows

Damit das Programm funktioniert, muss zuerst ein anderes Programm namens "Docker" installiert sein.

Docker kann auf folgender Website runtergeladen werden:

**https://www.docker.com/products/docker-desktop** oder klicken Sie [hier](https://www.docker.com/products/docker-desktop) um direkt auf die Website geleitet zu werden.

- Klicken Sie auf den "Download for Windows"-Knopf wie im nachstehenden Bild.

![DockerWebsite](img/docker_website.png?raw=true)

Danach wird das Programm Docker heruntergeladen. Sie werden eine Datei namens "Docker Desktop Installer", in Ihrem
Download-Ordner im Explorer finden wie auf folgendem Bild zu sehen ist:

![DockerInstallationDir](img/docker_installation_exe.png?raw=true "Pfad zur Installationsdatei")

- Mit einem Doppel-Klick auf diese Datei öffnet sich ein Fenster und Sie starten somit den Installationsprozess.

In diesem neuen Fenster gibt es zwei Menüpunkte zum ankreuzen. Achten Sie darauf das **beide** Optionen angelickt haben.
Dies sollte wie folgt aussehen:

![DockerInstallationTickStart](img/install_docker_tick_options.png)

Die Installation startet nun nachdem Sie auf **OK** rechts unten geklickt haben.
Nachdem die Installation fertig ist, erscheint in dem Fenster eine Meldung
"Close and Restart".

- Drücken Sie auf dieses Knopf, dies bewirkt, dass Windows neu gestartet wird
und der Installtionsprozess vollständig abgeschlossen wird.

![DockerInstallationFinish](img/restart.png)

Achten Sie darauf das dass Programm Docker gestartet ist. Klicken Sie mit einem Doppel-Klick auf das Programm, welches nun auf Ihrem
Desktop zu sehen ist. Das Fenster das aufgeht können Sie minimieren oder so lassen wie es ist.

## GHC Control Installation

Da nun Docker installiert ist, muss die eigentliche Software für die Videowall installiert werden.

- Kopieren Sie den gesamten Ordner, welcher das Programm enthält, vom USB-Stick auf Ihren Desktop.

- Navigieren Sie nun in Ihrem Windows-Explorer in den Ordner, welchen Sie eben erst auf den Desktiop kopiert haben. Dies könnte wie
folgt aussehen:

![GHCControlPath](img/ghc_control_path.png)

- Drücken Sie nun die Shift-Tast, welche sich auf der Tastatur links über der "STRG"-Taste befindet und machen Sie gleichzeitig einen
rechten Mausklick.

- Nun öffnet sich ein kleines Fenster und Sie müssen auf "PowerShell-Fenster hier öffnen" klicken. Genauer in folgendem
Bild dokumentiert:

![OpenPowerShell](img/open_ps.png)

- Danach öffnet sich ein Fenster welches folgend aussieht:

![PowerShellWithPath](img/powershell.png)

- Geben Sie in diesem Fenster nun folgenden Befehl ein und drücken Sie dann die "Enter"-Taste

`make install`

![PowerShellWithPath](img/make_install.png)

- Warten Sie nun einige Minuten bis das Programm fertig installiert ist.

Wenn die Installation fertig ist, was eine Weile dauern kann, muss am Ende der PowerShell so etwas stehen:

![PowerShellWithPath](img/make_install_finish.png)

## Starten des Programms

Wenn alle Schritte bis jetzt korrekt ausgeführt worden sind. Können Sie das Programm nun öffnen.

- Dazu öffnen Sie einen Browser Ihrer Wahl, wie zum Beispiel Google Chrome oder Edge, und tippen oben in die Adressleiste
des Browsers folgendes ein:

`localhost`

Nun könnte es ein paar Sekunden bis zu einer Minute dauern, dann hat das Programm im Browser geladen und wurde richtig installiert.