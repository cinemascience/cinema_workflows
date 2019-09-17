# An ASCENT example

This example takes as input a Cinema database produced by ASCENT (https://github.com/Alpine-DAV/ascent), computes several values on the images, and installs a Cinema viewer that includes a query on several variables.

The **task** for this workflow is to **quickly view and explore the results of the simulation, filtered by some computed values**. In this case, we use the `cinema` command line tool to compute the entropy and unique pixels of an image, and then view results constrained by values of the computed quantities. This can show us which images may be of interest, from the thousands of images that may be written into a Cinema database. 

This example can be easily adjusted to compute different quantities, and filter on different values, so it serves as a general example of a workflow that performs a visual query on a Cinema database.

