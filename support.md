---
title: Support – NetScanner
---

# Support – NetScanner

NetScanner für iPhone, iPad und Mac. Bei Fragen, Fehlern oder Wünschen schreib an
**app.sascha@icloud.com**. Bitte nenne dabei das Gerät, die iOS- bzw. macOS-Version und die
App-Version (steht in der Info-Ansicht der App).

Die [Datenschutzerklärung](datenschutz) findest du hier.

## Häufige Fragen

### Der Scan findet keine Geräte.
Die App braucht die Berechtigung **„Lokales Netzwerk“**. Ohne sie verwirft das System die
Anfragen an Geräte im Heimnetz. Prüfe unter *Einstellungen → Datenschutz & Sicherheit → Lokales
Netzwerk*, ob NetScanner aktiviert ist. Das Gerät muss außerdem im selben WLAN sein wie die Geräte,
die du suchst.

### Warum fehlen manche Geräte?
- Geräte im Tiefschlaf (z. B. batteriebetriebene Türschlösser) antworten nicht und können nicht
  erscheinen.
- Gäste- oder IoT-WLANs liegen oft in einem anderen Netz oder sind vom Hauptnetz getrennt. Dann sind
  ihre Geräte vom gescannten Netz aus nicht erreichbar.
- Ein Scan kann länger dauern, weil die App Geräte auch dann sucht, wenn sie nicht auf Ping antworten.
  Warte, bis der Scan fertig ist.
- Mit dem Router-Zugang (nur für FRITZ!Box) zeigt die App auch Geräte aus der Geräteliste der Box.

### Warum fehlt bei manchen Geräten der Hersteller?
iPhones, iPads und viele andere Geräte nutzen eine zufällige („private“) WLAN-Adresse. Zu ihr gibt es
keine Herstellerangabe. Zeigt ein Gerät sonst Namen oder Modell (etwa über Bonjour), nutzt die App
diese Angaben für eine Zuordnung. iOS gibt MAC-Adressen fremder Geräte nicht an Apps heraus; die App
ermittelt sie aus Bonjour, UPnP, NetBIOS oder der Geräteliste des Routers.

### Wofür braucht die App den Standort?
Nur damit das System den **Namen und die Signalqualität des WLANs** herausgibt. Die App liest keine
Standortkoordinaten und speichert oder überträgt keinen Standort.

### Was passiert beim Speedtest mit meinen Daten?
Der Speedtest nutzt den offenen Messdienst von Measurement Lab (M-Lab). Dabei überträgt die App je nach
Anschluss mehrere hundert Megabyte, im Mobilfunk kann das dein Datenvolumen belasten. M-Lab
veröffentlicht die Messergebnisse samt IP-Adresse als offene Daten. Der Test startet nur, wenn du auf
„Start“ tippst.

### Wie funktioniert der Router-Zugang?
Er ist optional und für FRITZ!Box-Router gedacht. Du trägst Adresse, Benutzername und Passwort ein.
Die App liest damit die Geräteliste direkt von deiner Box. Das Passwort liegt im Schlüsselbund deines
Geräts und wird nur an deinen eigenen Router gesendet. Auf der Box muss der Zugriff für Anwendungen
(TR-064) erlaubt sein.

### Die App stürzt ab oder zeigt etwas Falsches an.
Schreib uns bitte, was du gemacht hast, kurz vor dem Absturz. Hilfreich ist die Absturzmeldung:
*Einstellungen → Datenschutz & Sicherheit → Analyse & Verbesserungen → Analysedaten*, Eintrag
„NetScanner“.
