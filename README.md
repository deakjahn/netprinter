# NetPrinter

### Network printing made simple

Do you have a printer, maybe an older one, that you would like to print to from your phone or tablet? An inkjet or a black-and-white or color laser? Something even its manufacturer doesn't support any more? Or they want to force you to subscribe to some cloud printing service to use it?

This is an app to allow you to print to a network printer directly from your device. Yes, on your home or office network, behind your own router and firewall. There is no cloud, nothing uploaded, nothing sent out, no registration, no external service to depend upon: everything happens on your own internal network – between your device and your printer.

Just check that your printer understands one of the many supported printer languages directly:

- PDF
- PWG (IPP Everywhere)
- PCLm, PCLmS (Mopria)
- Airprint/URF (Apple)
- PostScript
- PCL 3 GUI (Hewlett-Packard)
- PCL 5/5c (Hewlett-Packard)
- PCL 6e/XL (Hewlett-Packard)
- HP-GL/2 RTL (Hewlett-Packard)
- ESC/P2 (Epson)
- ESC/P-R (Epson)
- ESC/PAGE (Epson)
- GDI host-based (many)
- XPS (Windows)
- ESC/POS (Epson)
- P-Touch (Brother)
- StarPRNT (Star Micronics)
- TSPL/TSPL2 (TSC)
- ZPL, EPL (Zebra)

and it's connected to your local network (or your device) using one of the many supported connections:

- Ethernet
- WiFi
- WiFi Direct
- Bluetooth
- USB OTG (On-The-Go)

and protocols:

- RAW (JetDirect, AppSocket, Port 9100, TCPmon)
- LPD/LPR
- IPP/CUPS (Linux or Mac)
- Samba (Windows)
- WSD (Windows)
- UPnP
- FTP

You can configure the printer manually or automatically with:

- Bonjour/Avahi/ZeroConf
- WiFi Direct/Mopria
- Bluetooth, Smart/LE
- IPP/CUPS
- Samba
- WSD
- UPnP

The app adds all your configured printers to Android and they will be available for any app that's capable to print: be it an e-mail app, calendar, document editor, game or whatever else.

The paid version, in addition to removing the ads, rewards your support with several extra features:

- use the server mode (see below),
- when you print several images to a page, they are printed in a collage layout instead of a simple, boring grid, with adaptive sizes to show each image in full, without cropping;
- you can select from several display (dithering) options to make printing both black-and-white and colored image material much more interesting;
- you can enlarge a smaller page to fit the page size of the printer;
- you can change the brightness of the printout;
- you can use non-uniform printer resolutions.

## Server mode

The app is also capable of the reverse operation: instead of printing to a printer on your network, it can provide the print server that you can print to from your other network devices. Practically, you can connect your printer with an USB OTG adapter to your phone (maybe to an older phone no longer used) and it will become a full-fledged print server supporting the protocols above, accepting incoming print jobs from all your other mobile devices or computers, too.

## Beta program

If you find problems with your printer and you're willing to experiment a little, please, consider joining the [beta program](https://play.google.com/apps/testing/hu.co.tramontana.netprinter). The development version might already offer better support or more features for your printer and your feedback will help us make the app even better.
