---
title: Privacy Policy – NetScanner
---

# Privacy Policy – NetScanner (iPhone, iPad and Mac)

*This is a translation of the German original, [Datenschutzerklärung](datenschutz). In case of doubt, the German version applies.*

Last updated: 24 October 2026

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
  manufacturer details of the devices in your local network. The data is only kept in memory
  for display. It is gone when you quit the app. If you export results as CSV, you decide where
  the file goes.
- **Local network:** The app needs the “Local Network” permission (iOS or macOS) to find devices
  in your home network. The scan sends ping, TCP and UDP requests (for example mDNS, NetBIOS,
  SSDP) to addresses in your own network to find active devices, names and manufacturers. These
  requests do not leave your network.
- **Network tools:** Ping, DNS lookup, traceroute, speed test and “Public IP” only run when you
  start them. Their results (for example response times, route, speed test measurements) are
  only kept in memory for display. The app only remembers the display style you chose for the
  speed test (gauge or bars) on your device.
- **Wi-Fi information and location (iPhone, iPad and Mac):** To show the Wi-Fi name and
  connection quality, the system (iOS or macOS) requires the “Location” permission (While Using
  the App). The app does not read location coordinates and does not store or transmit a location.
- **Router access (optional, iPhone, iPad and Mac):** If you enter the address, username and
  password of your router, the app reads the device list directly from your router. The
  credentials are only stored on your device (passwords in the keychain of iOS or macOS) and
  only sent to your own router.
- **Mac version:** The Mac app offers the same features as the iPhone and iPad app (network
  scan, network tools, Wi-Fi display, router access). It runs in the macOS app sandbox. It
  determines MAC addresses from Bonjour, UPnP, NetBIOS or the router’s device list; it does not
  read the Mac’s ARP table.

## 4. Requests to external services

For the “Public IP” (including the provider display) and “Speed test” features, the app sends
requests to services on the internet. For technical reasons, these services see your public IP
address:

| Service | Purpose |
|---|---|
| ipify.org (api.ipify.org, api6.ipify.org) | Determining your public IPv4/IPv6 address |
| ipwho.is, with ipinfo.io as fallback | Assigning the public IP to a provider (ISP), AS number and rough location |
| Measurement Lab (M-Lab): locate.measurementlab.net and the measurement server assigned from there | Speed test: finding the nearest server and measuring download, upload and latency with the open NDT7 test |

These requests are only triggered when you open or refresh the “Public IP” tool or tap “Start”
in the speed test. No further data (name, device ID, network data) is sent along. The services
are operated by third parties. Their own privacy policies apply to their data processing.

**Speed test and Measurement Lab:** A speed test transfers test data for about 10 seconds each
in download and upload. Depending on your connection, this is several hundred megabytes; on a
mobile network it can use up your data volume. According to its own privacy policy, Measurement
Lab keeps the results of its measurements indefinitely and makes them publicly available as open
research data. This includes your IP address and the date and time of the measurement. The speed
test only starts when you tap or click “Start”, and the app points out this publication in the
speed test window. If you do not want this, do not start the speed test. Details and information
on exercising your rights can be found at <https://www.measurementlab.net/privacy/>.

**Ping, DNS lookup and traceroute:** With these tools the app sends requests to the target you
enter and, for traceroute, to the routers on the way there. Name resolution is handled by the DNS
server of your network. These requests go directly from your device to the respective target and
not to the developer.

The legal basis is Art. 6(1)(b) GDPR (providing the feature you called up).

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
