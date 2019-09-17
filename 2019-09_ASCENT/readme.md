# An ASCENT example

This example takes as input a Cinema database produced by ASCENT (https://github.com/Alpine-DAV/ascent), computes several values on the images, and installs a Cinema viewer that includes a query on several variables.

The **task** for this workflow is to **quickly view and explore the results of the simulation, filtered by some computed values**. In this case, we use the `cinema` command line tool to compute the entropy and unique pixels of an image, and then view results constrained by values of the computed quantities. This can show us which images may be of interest, from the thousands of images that may be written into a Cinema database. 

This example can be easily adjusted to compute different quantities, and filter on different values, so it serves as a general example of a workflow that performs a visual query on a Cinema database.

## To use this workflow:

1. Clone this repository.
2. Install `cinema` [command line tool](https://github.com/cinemascience/cinema_lib). Make sure to install numpy to activate the image-based options. You will know it's installed properly if command line options like `--image-entropy` show up when you type `cinema --help` after installing it.
3. Using a shell or terminal window, clone this repository, and then `cd` into it.
4. Copy a Cinema database created with ASCENT into this directory.
5. Type `./run <database name>`
6. When the script is complete, you can view the `explore.html` file in a browser (check settings per the [cinema explorer](https://github.com/cinemascience/cinema_explorer) instructions if you have any problems.




