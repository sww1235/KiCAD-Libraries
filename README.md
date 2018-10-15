# KiCAD-Libraries


These are KiCAD libraries that I have created during various projects. Feel free
to use them under the repo license.

I try to be completely accurate but some errors may have crept in. Please file a
github issue if you find an error.

If you find them useful, please let me know.

Please be careful of 3d model files included in these repos. In general they
should be safe to use, but I may have utilized some from manufacturers that
might have some licensing issues. I will endevour to fix or highlight these
issues as I come across them. Personally I could not care but I am including
this as a warning to others who may use these libraries.

## Description of Libraries

There may be a discrepancy between the library that a schematic part is in and
its footprint is in. Footprints will generally be more specific while parts,
especially jacks and switches will be generic so as to fit into KiCAD's library
management philosopy.

I try to keep connectors and switches in their own generic libraries so
manufacturer specific libraries only contain chip pinouts.

All libraries with a manufacturer's name will contain only parts from that
manufacturer.

Specific libraries are discribed below.

### SW-Con

This library contains various connectors and jacks. These may be generic or
manufacturer specific.

### SW-gElectroMech

This library contains generic electromechanical parts such as relays, switches
and speakers.

### SW-gTransistors

This library contains generic transistor schematic symbols.

### SW-Passives

This library contains various passive components, especially smaller variants of
existing components.

### SW-power

This library contains custom power pins that I have needed for various projects.
