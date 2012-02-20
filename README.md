# mk1click

Shell script for creating Pharo 1-click images from Pharo Jenkins server.

Supporting files taken from official Pharo 1.3 1-click image.

## Description

Downloads Jenkins CI builds of Linux and MacOS Cog VM builds, together with Pharo 1.4 image.

Unpacks and shuffles the resulting files into a structure based on the official Pharo 1.3 1-click image.

Note that Windows VM is currently *not* included.  If there is an official place to get this, it can easily be added.

## To use

    ./mk1click

You should end up with a file `Pharo-1.4-nightly-OneClick.zip` in the current directory.

## License

Released under the MIT license to match Pharo.