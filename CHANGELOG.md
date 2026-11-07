# Changelog

## [2.49.0] - 2026-11-06

* Fixed: attaching log with some mailers
* Fixed: PCLmS printers
* Added: full AirPrint support
* Added: reverse order printing
* Added: manual duplex (premium)
* Added: imposition in extra options (premium)
* Added: allow save log if e-mail send fails
* Improved: dropdown lists
* Fixed: platform activity lifecycle

## [2.48.0] - 2026-10-20

* Fixed: matching incoming printers to known ones
* Improved: refactor discovery
* Improved: Bluetooth permissions on newer Androids

## [2.47.0] - 2026-10-16

* Added: format database inside app
* Fixed: some GDI printers (QPDL, TSPL)

## [2.46.0] - 2026-10-13

* Fixed: host name in IPPS/HTTPS/WSD
* Fixed: DNS lookups with timeout
* Added: label gap (TSPL)
* Improved: GDI model list visibility of filtered items

## [2.45.0] - 2026-10-09 beta

* Fixed: extra items in More options (premium version)
* Improved: internal platform communication
* Improved: shared file UI
* Improved: preferences handling
* Improved: smoother start with ads
* Improved: app start in dark mode
* Improved: Android printer handling (stale printers)
* Improved: job pooling (stale jobs)

## [2.44.0] - 2026-09-30

* Fixed: IP address error (String/Map cast)
* Fixed: help documents text color in dark mode

## [2.43.0] - 2026-09-28

* Improved: privacy policy UI (Huawei)

## [2.42.0] - 2026-09-26

* Fixed: privacy policy UI (Huawei)

## [2.41.0] - 2026-09-24

* Improved: full IPv6 support
* Added: privacy policy (Huawei) 
* Fixed: URF size error
* Fixed: LPR chunked receive

## [2.40.0] - 2026-09-12

* Fixed: startup crash

## [2.39.0] - 2026-09-11

* Added: support for more GDI printers (lidil.2)
* Added: duplex mirroring (PS/PDF)

## [2.38.0] - 2026-05-06

* Added: support for more GDI printers (lidil.1)
* Fixed: IPv6 IPP printer uri

## [2.37.0] - 2026-04-07

* Added: support for more GDI printers (capt.3)
* Fixed: timing errors of router-hosted LPR
* Fixed: render matrix transforms

## [2.36.0] - 2026-03-15

* Fixed: support for some GDI printers (capt.2)

## [2.35.0] - 2026-03-05

* Fixed: timing errors of router-hosted RAW
* Fixed: support for some GDI printers (pixma)

## [2.34.0] - 2026-02-27

* Improved support for ESC/P printers
* Fixed: support for some GDI printers (pixma)

## [2.33.0] - 2026-02-15

* Added: automatic GDI printer selection
* Improved: GDI printer selection with search
* Fixed: support for some GDI printers (km, hiperc)

## [2.32.0] - 2026-01-31

* Added: support for more GDI printers (km)
* Fixed: support for some GDI printers (hiperc)

## [2.31.0] - 2026-01-20

* Fixed: print page ranges
* Fixed: PrintDocument JBIG regression
* Added: support for more GDI printers (pana)

## [2.30.0] - 2025-12-25

* Added: simulated copies
* Added: user selectable font (premium version)
* Added: PCL4, ESC/P formats
* Added: quick actions
* Improved: crash resilience
* Improved: JmDNS for Bonjour/Avahi
* Added: server mode Driverless-compatible (AirPrint on rooted), accepts PDF/PWG/PCLm/JPG/URF?
* Fixed: WSD discovery
* Fixed: landscape printing
* Improved: server WSD support
* Improved: splash screen on newer Androids
* Improved: service stops with app

## [2.29.2] - 2025-10-14

* Fixed: SharedPreferences regression

## [2.29.1] - 2025-10-11
## [2.29.0] - 2025-10-03 beta

* Improved: edge-to-edge design
* Added: repeated discovery in server mode
* Added: USB auto-attach
* Fixed: consent dialog (EU/US) always suppressed in premium
* Fixed: USB connection lost
* Improved: receiving shared files
* Improved: splash screen
* Improved: smoother display of ads

## [2.28.0] - 2025-09-13

* Added: support for more GDI printers (sgraster, capt)
* Fixed: support for some GDI printers (hbpl)
* Improved: logging for server

## [2.27.0] - 2025-08-06

* Added: support for more GDI printers (ufr2, lipslx)
* Updated: Google libraries

## [2.26.0] - 2025-07-06

* Added: support for more GDI printers (brjpc, xl2hb)
* Fixed: support for some GDI printers (brl)

## [2.25.0] - 2025-04-29

* Added: N-up printing and imposition (premium version)
* Fixed: landscape printing
* Fixed: Samba with anonymous/guest access
* Fixed: wifi discovery error on VPN (NetworkCapabilities.transportInfo)
* Improved: low-memory (banded) printing as user setting

## [2.24.0] - 2025-04-03

* Improved: support for paper source (tray 1-3)
* Improved: margin with units

## [2.23.0] - 2025-03-29

* Fixed: printing error
* Fixed: print from activity context (share file)
* Improved: support for paper source

## [2.22.0] - 2025-03-27

* Added: support for paper source

## [2.21.0] - 2025-02-08

* Added: support for more label printers (dymo)
* Improved: discovery for missing printers before removal
* Improved: IPP error messages on invalid attr

## [2.20.2] - 2025-01-08 beta

* Improved: "text" dithering

## [2.20.0] - 2025-01-07

* Fixed: EPL printing

## [2.19.3] - 2025-01-03

* Improved: LPR timeout

## [2.19.2] - 2024-12-23

* Fixed: sending log from Settings page

## [2.19.1] - 2024-12-11

* Fixed: share and server mode incompatible
* Added: printer list swipe left: edit
* Improved: hero animation in edit

## [2.19.0] - 2024-12-01 beta

* Added: send/save print file (premium version)
* Improved: hierarchy of transport and protocol
* Improved: display permission during USB discovery
* Improved: setup guide without embedded browser
* Fixed: safe MIME in IPP printing with some printers
* Fixed: USB printing
* Fixed: Wi-Fi Direct printing on Android 10+

## [2.18.0] - 2024-11-08

* Fixed: freezing in network print
* Improved: server messages

## [2.17.0] - 2024-11-01

* Changed: app icon
* Improved: memory usage (JPG)
* Improved: server messages
* Removed: unnecessary external storage permission
* Added: SDK 34 foreground service permission
* Fixed: Discovery search back button
* Fixed: IPP discovery with multiple printers
* Added: Privacy policy
* Fixed: some GDI printers (zjs)

## [2.16.0] - 2024-10-15

* Fixed: brightness in BW
* Fixed: some GDI printers (hp)
* Fixed: platform error mesages to log

## [2.15.1] - 2024-09-27

* Removed: detailed logs setting, now default
* Improved: platform error mesages to log
* Fixed: crash in Android/X86 (Wi-Fi p2p manager)

## [2.14.1] - 2024-09-14 beta

* Added: brightness (premium version)
* Added: logging from platform side
* Improved: notification status messages
* Fixed: duplex (brl)

## [2.14.0] - 2024-09-11

* Fixed: crash when leaving server advertise screen
* Fixed: mirrored when printing duplex on non-duplex printers
* Improved: lost communication between app parts
* Improved: Android notification about printing
* Improved: server initialization

## [2.13.0] - 2024-09-09

* Fixed: occasional corrupt (banded) printing
* Fixed: USB permission on Android 14
* Fixed: some GDI printers (pixma)
* Improved: printer format recognition (versioned command sets)
* Added: wake lock during printing

## [2.12.2] - 2024-08-07

* Fixed: some GDI printers (pixma)

## [2.12.1] - 2024-08-05 apk

* Fixed: IPPS host name resolution
* Improved: ordered dither (clustered)

## [2.12.0] - 2024-07-30 beta

* Improved: printer format recognition
* Improved: detailed logs defaults to on
* Fixed: memory management issues
* Fixed: support for some GDI printers (pantum, hiperc)
* Fixed: protocol timeouts
* Fixed: UI focus when error

## [2.11.1] - 2024-05-05 beta

* Fixed: IPP: MIME of GDI printers

## [2.11.0] - 2024-06-04

* Added: support for more GDI printers (ddst2)
* Fixed: GDI compression error (brl)

## [2.10.0] - 2024-06-02

* Added: support for more GDI and label printers (brpj, ptouch, epl)
* Fixed: cached Flutter engine lost connection
* Fixed: GDI: split manufacturers with many printers
* Fixed: margin on label printers

## [2.9.0] - 2024-05-27

* Added: support for more GDI printers (pixma)
* Fixed: Bluetooth initial permission

## [2.8.1] - 2024-05-20

* Fixed: Bluetooth printing
* Improved: different JPG/PNG converter (Java instead of C++/JNI)

## [2.8.0] - 2024-05-17

* Added: Bluetooth support
* Improved: PCL5 compression

## [2.7.0] - 2024-05-09

* Improved: test page quality
* Fixed: multiple addresses in WSD discovery
* Fixed: WSD printing
* Fixed: IPP discovery of standalone printers
* Fixed: IPP media sizes
* Fixed: PCL3GUI 600 dpi out of memory
* Fixed: PCL paper size

## [2.6.0] - 2024-05-02

* Fixed: GDI formats (qpdl)

## [2.5.2] - 2024-04-20

* Fixed: IPP security, handling of certificates
* Fixed: GDI page size (brl, kpsl)
* [Huawei] Improved: catching up
* Improved: GDPR consent in Settings
* Added: Chinese localization

## [2.4.0] - 2024-04-07

* Improved: IPP security and authentication (client, server)
* Fixed: USB discovery with missing names

## [2.3.1] - 2024-04-02

* Fixed: PCL5 page size

## [2.3.0] - 2024-03-28 beta

* Added: XPS print format
* Fixed: extra options dialog
* Added: size test page
* Fixed: fit to page sizing
* Fixed: PS page size

## [2.2.3] - 2024-03-15

* Fixed: IPP response

## [2.2.2] - 2024-03-15 beta

* Fixed: USB queued send

## [2.2.1] - 2024-03-13 beta

* Fixed: USB timeout
* Added: IPP status message in log

## [2.2.0] - 2024-02-23

* Added: support for more GDI printers (Pantum zjs)
* Fixed: support for some GDI printers (kpsl)

## [2.1.0] - 2024-02-03

* Added: support for more GDI printers (kpsl)
* Fixed: size error with last band of rendering

## [2.0.0] - 2024-01-23

* Added: server mode (premium version)
* Added: UPnP, WSD discovery
* Fixed: printers with same weight overwrote each other
