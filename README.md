# MatchVision

MatchVision liest Anzeigetafeln in Echtzeit: Spielstand, Uhr, Namen und alles, was sonst auf der Tafel steht. Die Werte gibt es an andere Programme weiter, zum Beispiel an eine Grafik im Livestream.

Aktuelle Version: **0.5.0**

## Installieren

1. [MatchVision-Setup.exe herunterladen](https://github.com/thecrafti87/MatchVision-Releases/releases/latest/download/MatchVision-Setup.exe)
2. Die Datei doppelklicken und „Weiter" bis zum Ende. Administrator-Rechte sind nicht nötig.
3. MatchVision steht danach im Startmenü und, wenn gewünscht, auf dem Desktop.

Windows kann beim Start der Setup-Datei fragen, ob sie ausgeführt werden soll, weil sie nicht signiert ist. Über „Weitere Informationen" und „Trotzdem ausführen" geht es weiter.

Entfernen: in Windows unter „Einstellungen → Apps" oder im Startmenü über „MatchVision entfernen". Dabei wird gefragt, ob auch Felder und Einstellungen gelöscht werden sollen.

### Ohne Installation

Wer nichts installieren will: [MatchVision.zip](https://github.com/thecrafti87/MatchVision-Releases/releases/latest/download/MatchVision.zip) herunterladen, in einen Ordner entpacken, in den du schreiben darfst (zum Beispiel „Dokumente", nicht „Programme"), und dort `MatchVision.exe` doppelklicken.

Gebraucht wird Windows 10 oder 11 (64 Bit). Für NDI-Quellen muss zusätzlich NDI Tools installiert sein.

## Neue Versionen

MatchVision sieht beim Start selbst nach, ob es eine neue Version gibt, und zeigt dann oben im Fenster einen Hinweis. Installiert wird erst nach einem Klick auf „Jetzt aktualisieren". Felder und Einstellungen bleiben erhalten.

Wer lieber von Hand aktualisiert: die neue Setup-Datei ausführen oder die neue `MatchVision.zip` über den alten Ordner entpacken. Felder und Einstellungen (`config.json`, `api_token.secret`) sind in keinem Paket enthalten und bleiben, wie sie sind.

## Was steckt drin

In diesem Repository liegen nur die fertigen Programme, nicht der Quellcode. Die Lizenzen der mitgelieferten Bibliotheken stehen im Programmordner unter `Lizenzen`.

NDI® ist eine eingetragene Marke der Vizrt NDI AB.
