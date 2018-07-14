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
printed.

## Motivation

While I was not employed as a developer at the time, I was studying towards
my Computing and IT degree with a focus on Java and was keen to find a place
to apply these skills. The second application mentioned above, not built be me,
was the only one provided by the library's IT department and it was frankly
insufficient. While the system did generate the stacks automatically, this was
based on the assumption that the metadata collected about each item was
correct, which it often wasn't. This meant that the items in each stack would
have to be changed, a process that could only be completed while in an
internet-connected office. This essentially meant we were left with a pen and
paper solution, where staff would have to print out stack lists, go and find
those items, realise they didn't fit, attempt to locate alternatives (referring
to another paper list) then write down the barcode numbers and return to the
office to manually key them in. In such a large building this was a ridiculous
solution.

This isn't necessarily a criticism of the individual staff members that
developed this solution. Rather, the library's IT departments are grosly
understaffed and underfunded, leading to inefficient and often broken solutions
throughout. In any case, I genuinely belive that the newspaper moves project
would not have been completed in time had we relied on the system provided.

## Reports

The application generated inventory reports that were sent with each vehicle.

- [20-Aug-2014](reports/inventory-20-Aug-2014.pdf)

As a supplementry function, statistical reports were generated as PDFs and
presented to the project board.

- [18-Mar-2014](reports/stats-18-Mar-2014.pdf)
- [14-Apr-2014](reports/stats-14-Apr-2014.pdf)
- [11-Nov-2014](reports/stats-11-Nov-2014.pdf)

## Version

Unfortunately, as this application was built in 2014, before I began using git
for version control, I could not find the final version of the application.
The version included here was still a work in progress but gives some idea
of what was built.

Further, I compiled the application as a Windows executable for distribution
and this compiled version is all that I could find.
