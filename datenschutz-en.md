---
title: Privacy Policy – NetScanner
---

# Privacy Policy – NetScanner (iPhone, iPad and Mac)

*This is a translation of the German original, [Datenschutzerklärung](datenschutz). In case of doubt, the German version applies.*

Last updated: 2 November 2026

## 1. Controller

Sascha Z.
Wilhelmhofallee 68, 47799 Krefeld, Germany
Email: app.sascha@icloud.com

## 2. Principle

NetScanner does not collect, store or transmit any personal data to the developer. There are no
user accounts, no advertising, no tracking and no third-party analytics or crash-reporting
services. All results of a network scan stay on your device.

## 3. What the app processes on your device

- **Network scan:** IP addresses, hostnames, response times, open ports, MAC addresses and
  manufacturer details of the devices in your local network. The data is kept in memory for
  display. In addition, the app adds an entry to the scan history after a scan (see below). If
  you export results (CSV, PDF or JSON), you decide where the file goes.
- **Scan history and “My Devices”:** After each scan, the app stores on your device which devices
  (IP address, MAC address, name, manufacturer) were found in which network at what time, so it
  can detect new and missing devices. It also stores titles, notes and markers (“pinned”, “known
  device”) as well as custom device names and notes that you enter yourself. The last 50 scans
  per network are kept, at most 200 in total; pinned scans are always kept. The data only lives
  in your device’s protected app folder (no iCloud sync, no transmission). You can delete single
  scans, the history of a network and device entries in the app; deleting the app removes all
  of it.
- **Local network:** The app needs the “Local Network” permission (iOS or macOS) to find devices
  in your home network. The scan sends ping, TCP and UDP requests (for example mDNS, NetBIOS,
  SSDP) to addresses in your own network to find active devices, names and manufacturers. These
  requests do not leave your network.
- **Network tools:** Ping, DNS lookup, traceroute (also over IPv6), port check, web check,
  Bonjour browser, Wake-on-LAN, subnet calculator, speed test and “Public IP” only run when you
  start them. Their results (for example response times, route, certificate, ports) are only kept
  in memory for display. The exception is the speed test: the app stores its results (time,
  download, upload, latency, connection type, location of the measurement server) as a speed
  test history on your device (up to 200 entries, deletable one by one or all at once), as well
  as the display style you chose (gauge or bars).
- **Widgets and controls (iPhone and iPad):** The network widget and the speed test widget show
  the last known public IP address, the time and number of devices of the last scan and the last
  speed test measurement. For this, the app stores these values in a file in the shared folder
  (app group) of the app and the widget on your device. Other apps cannot access it. The Control
  Center controls only open the app. Section 4 describes how the widgets send requests to the
  internet.
- **Siri and Shortcuts:** The app’s actions (for example scan, ping, speed test, traceroute,
  public IP) run on your device. The app returns their result to Siri or the Shortcuts app; what
  you do with it is up to you.
- **Wi-Fi information and location (iPhone, iPad and Mac):** To show the Wi-Fi name and
  connection quality, the system (iOS or macOS) requires the “Location” permission (While Using
  the App). The app does not read location coordinates and does not store or transmit a location.
- **Router access (optional, iPhone, iPad and Mac):** If you enter the address, username and
  password of your router, the app reads the device list directly from your router. The
  credentials are only stored on your device (passwords in the keychain of iOS or macOS) and
  only sent to your own router.
- **Mac version:** The Mac app offers the same features as the iPhone and iPad app (network
  scan, network tools, Wi-Fi display, router access) without widgets, but with a menu bar
  item that shows the public IP address, the last scan and quick actions. When you open it, the
  app looks up the public IP address (see section 4). On request, the app starts at login (switch
  in the menu bar item; macOS lists it under “Login Items”, where you can turn it off at any time)
  and keeps running in the background so the menu bar item stays visible. The app runs in the
  macOS app sandbox. It
  determines MAC addresses from Bonjour, UPnP, NetBIOS or the router’s device list; it does not
  read the Mac’s ARP table.

## 4. Requests to external services

For the “Public IP” (including the provider display) and “Speed test” features and for the
widgets, the app sends requests to services on the internet. For technical reasons, these services see your public IP
address:

| Service | Purpose |
|---|---|
| ipify.org (api.ipify.org, api6.ipify.org) | Determining your public IPv4/IPv6 address |
| ipwho.is, with ipinfo.io as fallback | Assigning the public IP to a provider (ISP), AS number and rough location |
| Measurement Lab (M-Lab): locate.measurementlab.net and the measurement server assigned from there | Speed test: finding the nearest server and measuring download, upload and latency with the open NDT7 test |

These requests are triggered when you open or refresh the “Public IP” tool (also via the refresh
button in the network widget or by opening the menu bar item on the Mac) or tap “Start” in the
speed test or “Start Test” in the speed test widget. **Exception, network widget:** As long as
you have set up the network widget on your Home Screen, Lock Screen or in Today View, it looks
up your public IPv4 address at ipify.org about every 30 minutes (iOS decides the exact time),
even without the app being open, to keep it up to date. This background request only goes to
ipify.org, not to ipwho.is, ipinfo.io or Measurement Lab. It ends when you remove the widget.
No further data (name, device ID, network data) is sent along. The services
are operated by third parties. Their own privacy policies apply to their data processing.

**Speed test and Measurement Lab:** A speed test transfers test data for about 10 seconds each
in download and upload. Depending on your connection, this is several hundred megabytes; on a
mobile network it can use up your data volume. According to its own privacy policy, Measurement
Lab keeps the results of its measurements indefinitely and makes them publicly available as open
research data. This includes your IP address and the date and time of the measurement. The speed
test only starts when you tap or click “Start” or tap “Start Test” in the speed test widget,
and the app points out this publication in the speed test window. The speed test widget runs the
same measurement; it never starts it by itself. If you do not want this, do not start the speed test. Details and information
on exercising your rights can be found at <https://www.measurementlab.net/privacy/>.

**Ping, DNS lookup, traceroute, port check and web check:** With these tools the app sends
requests to the target you enter (the web check opens a connection and reads the TLS certificate
and HTTP headers) and, for traceroute, to the routers on the way there. Name resolution is handled by the DNS
server of your network. These requests go directly from your device to the respective target and
not to the developer.

The legal basis is Art. 6(1)(b) GDPR (providing the feature you called up or set up, for
example the widget).

## 5. No disclosure, no tracking

The developer receives no data from the app. There is no tracking within the meaning of Apple’s
App Tracking Transparency.

## 6. Your rights

Since the developer does not process any personal data, they cannot provide you with information
about it. You can revoke the permissions you granted in the settings of iOS or macOS at any time
and delete the app, which removes all locally stored data. You have the rights under the GDPR
(access, rectification, erasure, restriction, objection, complaint to a supervisory authority).

## 7. Changes

If the app is extended with features that transmit data, this policy will be adjusted beforehand.
