# panorama

Stitch multiple images into a single panorama.

The purpose of this script is to wrap around a number of Hugin scripts and stitch together images.
It is tuned to work with mircoscope images that form multiple rows of images with a small FOV (10 degrees)
and with fish eye effects.  These parameters can all be changed.

The output is all logged to a log file.  It also is designed to generate a cropped and uncropped image.  
Further, the PTO files are creates so that they can be used on images that have been colourized in order
to maintain the same spacial alignment.

To get assistance, run the command:
./panorama -h

# Requirement

This script requires the use of the Hugin tools for processing the images.  On Ubuntu, they can be installed with

sudo apt-get install hugin-tools

# Known Bugs
* Error messages sent to ErrorMsg and AssertNonZeroLen are not logged
* Does not check to make sure Hugin scripts are installed

# Todo
* Add support to write error messages to screen and log

# Licence
* GNU GPL V3 or later
* See the LICENCE file

# Maintainer
* John Peach <john@jppeach.com>
