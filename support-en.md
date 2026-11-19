---
title: Support – NetScanner
---

# Support – NetScanner

NetScanner for iPhone, iPad and Mac. If you have questions, find a bug or have a wish, write to
**app.sascha@icloud.com**. Please include the device, the iOS or macOS version and the app
version (shown in the app’s About screen).

You can find the [privacy policy](datenschutz-en) and the [legal notice](impressum-en) here. (German version: [Support](support).)

## Frequently asked questions

### The scan does not find any devices.
The app needs the **“Local Network”** permission. Without it, the system drops requests to
devices in your home network. Check under *Settings → Privacy & Security → Local Network*
whether NetScanner is enabled. The device must also be on the same Wi-Fi as the devices you are
looking for.

### Why are some devices missing?
- Devices in deep sleep (for example battery-powered door locks) do not answer and cannot appear.
- Guest or IoT Wi-Fi networks are often in a different network or separated from the main
  network. Their devices are then not reachable from the scanned network.
- A scan can take longer because the app also looks for devices that do not answer ping. Wait
  until the scan is finished.
- With router access (FRITZ!Box only), the app also shows devices from the box’s device list.

### Why is the manufacturer missing for some devices?
iPhones, iPads and many other devices use a random (“private”) Wi-Fi address. There is no
manufacturer information for it. If a device reports a name or model otherwise (for example via
Bonjour), the app uses that to guess. iOS does not release the MAC addresses of other devices to
apps; the app gets them from Bonjour, UPnP, NetBIOS or the router’s device list.

### Why does the app need the location?
Only so that the system releases the **name and signal quality of the Wi-Fi**. The app does not
read any location coordinates and does not store or transmit a location.

### What happens to my data in the speed test?
The speed test uses the open measurement service of Measurement Lab (M-Lab). Depending on your
connection, the app transfers several hundred megabytes; on mobile data this can use up your data
volume. M-Lab publishes the measurement results including the IP address as open data. The test
only starts when you tap “Start”.

### What happens to my data in Service Status?
Service Status retrieves the public status pages of the providers in the list directly from your device and
checks whether their services respond. The providers see your IP address; nothing is sent to the developer.
Requests are made when you open the tool for the first time, tap “Check Now” or add a provider or an address.
The app only queries further providers and your own addresses once you switch them on or enter them. You remove
your own addresses by swiping left.

### Service Status shows “Reachable”, but the provider has problems.
For an address you add yourself, the app can at first only check whether the page responds. It recognizes many
status pages automatically and shows their messages. For others, you also enter the address of an RSS or Atom
feed of the status page (`https` only). The app estimates from a message’s text whether it is an outage, so a
notice may occasionally be too cautious or missing. For the providers in the list, the icon next to the service
opens the provider’s status page.

### How does router access work?
It is optional and meant for FRITZ!Box routers. You enter the address, username and password. The
app uses them to read the device list directly from your box. The password is stored in your
device’s keychain and only sent to your own router. Access for applications (TR-064) must be
allowed on the box.

### The app crashes or shows something wrong.
Please tell us what you did just before the crash. The crash report helps:
*Settings → Privacy & Security → Analytics & Improvements → Analytics Data*, entry “NetScanner”.
