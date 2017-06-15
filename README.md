MakerBot Repliactor 2 Configurations
====================================

With Makerbot's declining support for the Replicator 2, but my machine still in good condition,
I try to come up with different workflows to get STL files into the printer.

As I get around to configure more tools, or change some configurations, I aspire to track those here.

Alternatives
------------

The following are out-of-the-box solutions which more or less "just" work.

 * MakerBot Print / MakerBot Desktop
   * First party toolchain
   * Closed source
   * "Print" software requires MakerBot account
 * ReplicatorG
   * Last updated 2012
   * Skeinforge Slicer (also somewhat defunct)
   * OSX Version on Java6 (deprecated)
   * Can be used as gcode to x3g converter (with its own quirks)

Cura + GPX
----------

This first workflow uses Ultimaker's cura (which has a very lively community, which I like) to slice
and GPX to convert gcode to x3g.

I originally used ReplicatorG to convert to x3g for the printer, but eventually I would like to automate
this with a cura plugin. Unfortunately, ReplicatorG's conversion cannot be called from the command line,
hence I ported my settings from there to GPX.

