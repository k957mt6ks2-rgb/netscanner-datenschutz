---
title: Datenschutzerklärung – NetScanner
---

# Datenschutzerklärung – NetScanner (iPhone, iPad und Mac)

Stand: 10.11.2026

## 1. Verantwortlicher

Sascha Z.
Wilhelmhofallee 68, 47799 Krefeld
E-Mail: app.sascha@icloud.com

## 2. Grundsatz

NetScanner erhebt, speichert und überträgt keine personenbezogenen Daten an den Entwickler.
Es gibt keine Benutzerkonten, keine Werbung, kein Tracking und keine Analyse- oder Absturz-
Dienste von Drittanbietern. Alle Ergebnisse eines Netzwerk-Scans bleiben auf deinem Gerät.

## 3. Was die App auf deinem Gerät verarbeitet

- **Netzwerk-Scan:** IP-Adressen, Hostnamen, Antwortzeiten, offene Ports, MAC-Adressen und
  Herstellerangaben der Geräte in deinem lokalen Netzwerk. Die Daten werden zur Anzeige im
  Speicher gehalten. Zusätzlich legt die App nach einem Scan einen Eintrag im Scan-Verlauf an
  (siehe unten). Exportierst du Ergebnisse (CSV, PDF oder JSON), entscheidest du, wohin die Datei
  geht.
- **Scan-Verlauf und „Meine Geräte“:** Nach jedem Scan speichert die App auf deinem Gerät, welche
  Geräte (IP-Adresse, MAC-Adresse, Name, Hersteller) in welchem Netz zu welchem Zeitpunkt
  gefunden wurden, damit sie neue und fehlende Geräte erkennen kann. Dazu kommen Titel, Notizen
  und Markierungen („festgehalten“, „bekanntes Gerät“) sowie eigene Gerätenamen und Notizen, die
  du selbst einträgst. Je Netz bleiben die letzten 50 Scans erhalten, insgesamt höchstens 200;
  festgehaltene Scans bleiben immer erhalten. Die Daten liegen nur im geschützten App-Ordner
  deines Geräts (kein iCloud-Abgleich, keine Übertragung). Du kannst einzelne Scans, den Verlauf
  eines Netzes und Geräteeinträge in der App löschen; mit dem Löschen der App verschwinden alle
  Daten.
- **Lokales Netzwerk:** Die App braucht die Berechtigung „Lokales Netzwerk“ (iOS bzw. macOS),
  um Geräte im Heimnetz zu finden. Der Scan sendet Ping-, TCP- und UDP-Anfragen (z. B. mDNS,
  NetBIOS, SSDP) an Adressen in deinem eigenen Netzwerk, um aktive Geräte, Namen und Hersteller
  zu finden. Diese Anfragen verlassen dein Netzwerk nicht.
- **Netzwerk-Werkzeuge:** Ping, DNS-Lookup, Traceroute (auch über IPv6), Port-Prüfung,
  Web-Prüfung, Mail-Prüfung, Bonjour-Browser, Wake-on-LAN, Subnetz-Rechner, Speedtest und „Öffentliche IP“
  laufen nur, wenn du sie startest. Ihre Ergebnisse (z. B. Antwortzeiten, Route, Zertifikat,
  Ports) werden nur zur Anzeige im Speicher gehalten. Ausnahme ist der Speedtest: Dessen
  Ergebnisse (Zeitpunkt, Download, Upload, Latenz, Verbindungsart, Standort des Messservers)
  speichert die App als Speedtest-Verlauf auf deinem Gerät (bis zu 200 Einträge, einzeln oder
  ganz löschbar), ebenso die gewählte Darstellung (Tacho oder Balken).
- **Widgets und Steuerelemente (iPhone und iPad):** Das Netzwerk-Widget und das Speedtest-Widget
  zeigen die zuletzt bekannte öffentliche IP-Adresse, Zeitpunkt und Anzahl der Geräte des letzten
  Scans sowie die letzte Speedtest-Messung. Dafür legt die App diese Werte in einer Datei im
  gemeinsamen Ordner (App-Gruppe) von App und Widget auf deinem Gerät ab. Andere Apps haben
  darauf keinen Zugriff. Die Steuerelemente im Kontrollzentrum öffnen nur die App. Wie die
  Widgets Anfragen ins Internet senden, steht in Abschnitt 4.
- **Siri und Kurzbefehle:** Die Aktionen der App (z. B. Scan, Ping, Speedtest, Traceroute,
  Öffentliche IP) laufen auf deinem Gerät. Ihr Ergebnis gibt die App an Siri bzw. die Kurzbefehle-App
  zurück; was du damit weiter machst, bestimmst du.
- **WLAN-Informationen und Standort (iPhone, iPad und Mac):** Für die Anzeige von WLAN-Name und
  Verbindungsqualität verlangt das System (iOS bzw. macOS) die Berechtigung „Standort“ (Beim
  Verwenden der App). Die App liest dabei keine Standortkoordinaten, speichert und überträgt
  keinen Standort.
- **Router-Zugang (optional, iPhone, iPad und Mac):** Wenn du Adresse, Benutzername und Passwort
  deines Routers einträgst, liest die App die Geräteliste direkt von deinem Router. Die
  Zugangsdaten werden nur auf deinem Gerät gespeichert (Passwörter im Schlüsselbund von iOS bzw.
  macOS) und nur an deinen eigenen Router gesendet.
- **Mac-Version:** Die Mac-App bietet dieselben Funktionen wie die iPhone- und iPad-App
  (Netzwerk-Scan, Netzwerk-Werkzeuge, WLAN-Anzeige, Router-Zugang) ohne Widgets, dafür mit einem
  Eintrag in der Menüleiste, der die öffentliche IP-Adresse, den letzten Scan und Schnellaktionen
  zeigt. Öffnest du ihn, fragt die App die öffentliche IP-Adresse ab (siehe Abschnitt 4). Auf
  Wunsch startet die App beim Anmelden (Schalter im Menüleisten-Eintrag; macOS führt sie dann
  unter „Anmeldeobjekte“, wo du es jederzeit ausschalten kannst) und läuft im Hintergrund weiter,
  damit der Menüleisten-Eintrag sichtbar bleibt. Die App läuft in der App-Sandbox
  von macOS. MAC-Adressen ermittelt sie aus Bonjour, UPnP, NetBIOS oder der Router-Geräteliste;
  die ARP-Tabelle des Macs liest sie nicht.

## 4. Abfragen bei externen Diensten

Für die Funktionen „Öffentliche IP“ (inklusive Anbieter-Anzeige), „Speedtest“ und die Widgets
sendet die App Anfragen an Dienste im Internet. Dabei sehen diese Dienste technisch bedingt deine öffentliche
IP-Adresse:

| Dienst | Zweck |
|---|---|
| ipify.org (api.ipify.org, api6.ipify.org) | Ermittlung deiner öffentlichen IPv4-/IPv6-Adresse |
| ipwho.is, ersatzweise ipinfo.io | Zuordnung der öffentlichen IP zu Anbieter (ISP), AS-Nummer und grobem Standort |
| Measurement Lab (M-Lab): locate.measurementlab.net und der von dort zugewiesene Messserver | Speedtest: Suche des nächstgelegenen Servers sowie Messung von Download, Upload und Latenz mit dem offenen Test NDT7 |

Diese Anfragen werden ausgelöst, wenn du das Werkzeug „Öffentliche IP“ öffnest oder
aktualisierst (auch über den Aktualisieren-Knopf im Netzwerk-Widget oder durch Öffnen des
Menüleisten-Eintrags auf dem Mac) bzw. im Speedtest auf „Start“ oder im Speedtest-Widget auf
„Test starten“ tippst. **Ausnahme Netzwerk-Widget:** Solange du das Netzwerk-Widget auf dem
Home-Bildschirm, im Sperrbildschirm oder in der Heute-Ansicht eingerichtet hast, ruft es auch
ohne geöffnete App etwa alle 30 Minuten (den genauen Zeitpunkt bestimmt iOS) deine öffentliche
IPv4-Adresse bei ipify.org ab, um sie aktuell anzuzeigen. Dieser Hintergrundabruf geht nur an
ipify.org, nicht an ipwho.is, ipinfo.io oder Measurement Lab. Er endet, wenn du das Widget
entfernst. Es werden keine weiteren Daten (Name, Geräte-ID, Netzwerkdaten) mitgesendet. Die Dienste werden von Dritten betrieben. Für deren
Datenverarbeitung gelten deren eigene Datenschutzerklärungen.

**Speedtest und Measurement Lab:** Ein Speedtest überträgt für jeweils etwa 10 Sekunden
Testdaten im Download und im Upload. Je nach Anschluss sind das mehrere hundert Megabyte, im
Mobilfunknetz kann das dein Datenvolumen belasten. Measurement Lab bewahrt die Ergebnisse
seiner Messungen laut eigener Datenschutzerklärung unbefristet auf und stellt sie öffentlich als
offene Forschungsdaten bereit. Dazu gehören deine IP-Adresse sowie Datum und Uhrzeit der
Messung. Der Speedtest startet nur, wenn du auf „Start“ tippst bzw. klickst oder im
Speedtest-Widget auf „Test starten“ tippst, und die App weist im Speedtest-Fenster auf diese
Veröffentlichung hin. Das Speedtest-Widget führt dieselbe Messung aus; es startet sie nie von
selbst. Wenn du das nicht möchtest, starte den
Speedtest nicht. Einzelheiten und Hinweise zur Ausübung deiner Rechte findest du unter
<https://www.measurementlab.net/privacy/>.

**Ping, DNS-Lookup, Traceroute, Port-Prüfung, Web-Prüfung und Mail-Prüfung:** Mit diesen Werkzeugen sendet die
App Anfragen an das Ziel, das du eingibst (bei der Web-Prüfung baut sie eine Verbindung auf und
liest TLS-Zertifikat und HTTP-Kopfzeilen), sowie bei Traceroute an die Router auf dem Weg dorthin. Die Namensauflösung
übernimmt der DNS-Server deines Netzwerks. Diese Anfragen gehen direkt von deinem Gerät an das
jeweilige Ziel und nicht an den Entwickler.

**Mail-Prüfung:** Die App fragt die DNS-Einträge der Domain ab, die du eingibst (MX, SPF, DKIM,
DMARC, MTA-STS, TLS-RPT und BIMI). Diese Abfragen laufen über den DNS-Server deines Netzwerks,
der sie sieht, und sind für den Entwickler nicht einsehbar. Hat die Domain eine MTA-STS-Richtlinie,
lädt die App sie per HTTPS von der Adresse `mta-sts.<Domain>` der eingegebenen Domain. Es werden keine
weiteren Daten übertragen, und die Ergebnisse werden nur zur Anzeige im Speicher gehalten.

Rechtsgrundlage ist Art. 6 Abs. 1 lit. b DSGVO (Bereitstellung der von dir aufgerufenen bzw.
eingerichteten Funktion, z. B. des Widgets).

## 5. Keine Weitergabe, kein Tracking

Der Entwickler erhält keine Daten aus der App. Es findet kein Tracking im Sinne von Apples
App Tracking Transparency statt.

## 6. Deine Rechte

Da der Entwickler keine personenbezogenen Daten verarbeitet, kann er dir dazu keine Auskunft
geben. Du kannst jederzeit die erteilten Berechtigungen in den Einstellungen von iOS bzw. macOS widerrufen
und die App löschen, wodurch alle lokal gespeicherten Daten entfernt werden. Dir stehen die
Rechte aus der DSGVO zu (Auskunft, Berichtigung, Löschung, Einschränkung, Widerspruch,
Beschwerde bei einer Aufsichtsbehörde).

## 7. Änderungen

Wird die App um Funktionen erweitert, die Daten übertragen, wird diese Erklärung vorher
angepasst.

## 8. Impressum

Anbieterkennzeichnung: [Impressum](impressum).
