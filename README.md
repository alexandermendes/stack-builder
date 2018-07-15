# stack-builder

> An application that was used to organise the BL Newspaper Moves project.

## Overview

In 2014, I built this Java Swing application to help organise the movement of
the British Library's newspaper collection Collindale to Boston Spa. It is
included here purely for posterity.

The application was loaded onto laptops and enabled staff to move around the
building and build stacks of collection items that would later be loaded onto
lorries. Taking a database of metadata about each collection item, such as
size, condition and location, the application would suggest nearby items that
were suitable for addition to the current stack. To add an item to a stack
staff would scan a barcode. A desktop application was chosen as the majority
of the building lacked a WiFi connection.

When enough stacks to fill a vehicle had been built, staff would return to an
office and run a process to assign an identifier to each stack and upload the
results to a remote database, making use of an application setup to assist the
newspaper moves project by the library's IT department (see below).

With all of the stacks to fill a vehicle recorded a set of reports could be
printed, such as the example inventory report below.

- [20-Aug-2014](reports/inventory-20-Aug-2014.pdf)

As a supplementry function, statistical reports were generated as PDFs and
presented to the project board.

- [18-Mar-2014](reports/stats-18-Mar-2014.pdf)
- [14-Apr-2014](reports/stats-14-Apr-2014.pdf)
- [11-Nov-2014](reports/stats-11-Nov-2014.pdf)

## Version

Unfortunately, as this application was built in 2014 (before I began using git
for version control) I could not find the final version of the application.
The version included here was still a work in progress but gives some idea
of what was built. Further, I compiled the application for distribution
using (using NetBeans, as far as I remember) and this compiled version is all
that I could find.
