# NetPrinter

### Print to your local printers locally

The purpose of this app is to allow you to print to a network printer directly from your device.
This means your home or office network, behind your own router and firewall. There is no cloud,
nothing uploaded, nothing sent out, no registration, no external service to depend upon: everything
happens on your own internal network.

This app is for you if you have a printer that understands any of the usual printer languages
directly:

- PDF
- PWG (IPP Everywhere)
- PCLm, PCLmS (Mopria)
- Airprint/URF (Apple)
- PostScript
- PCL 5/5c/6e/XL (Hewlett-Packard)
- GDI host-based (many)

and it's connected to your local network using any of the usual connections:

- Ethernet
- WiFi
- WiFi Direct

and protocols:

- RAW (JetDirect, AppSocket, Port 9100, TCPmon)
- LPD/LPR
- IPP/CUPS (Linux or Mac)
- Samba (Windows)
- FTP

You can configure the printer manually or automatically with:

- Bonjour/Avahi/ZeroConf
- WiFi Direct/Mopria
- IPP/CUPS
- Samba

The app adds all your configured printers to Android and they will be available for any app that's
capable to print: be it an e-mail app, calendar, document editor, game or whatever else.

The paid version, in addition to removing the ads, rewards your support with several extras features:

- when you print several images to a page, they are printed in a collage layout instead of a simple,
boring grid, with adaptive sizes to show each image in full, without cropping;
- you can select from several monochrome dithering options to make printing colored material
on a monochrome printer perfect;
- you can fit the printed content to the page size of the printer.

## Beta program

If you find problems with your printer and you're willing to experiment a little, please,
consider joining the beta program. The development version might already offer better support
or more features for your printer and your feedback will help us make the app even better.

### Version 1.19

This version is a major rewrite of the GDI printer support. These are host-based, Windows printers
that depend on their full printing knowledge built into the software driving them. The printer has no
printer language intelligence of its own and expects the full page to be rendered as a complete bitmap
on the host computer. This makes them both cheaper and relatively slow to print to, especially in color.

And precisely this was the reason for the rewrite. Up to 300 dpi, there's no change but above that,
the page is now rendered in stripes rather than in full. This reduces the memory requirements
dramatically because there's no need to keep the full, high resolution page in memory any more.
Also, it made it possible to utilize the multiple processor cores in today's mobile devices,
rendering in parallel, resulting in speedups of up to ten times in some cases. The bitmap compression
operations were also carefully optimized to avoid any time wasted by unnecessarily copying bitmap data
between the various stages of operation.

With a major rewrite, new bugs can creep in. Please, report any problems here so that it can be fixed
to arrive at an even better, more performant version of the app. Thanks for your help.
