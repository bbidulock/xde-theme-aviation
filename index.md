---
layout: default
---
[xde-theme-aviation -- read me first file.  2015-05-18]: #

xde-theme-aviation
===============

Package `xde-theme-aviation-1.1.5` was released under CCPL:cc-by-nc-nd-3.0
license 2015-05-18.

This is a theme and a set of backgrounds for the _XDE (X Desktop
Environment)_ that provides a set of backgrounds on
a Aviation theme.
This theme uses the Squared-grey style from the [`xde-styles`][11]
package.

The source for `xde-theme-aviation` is hosted on [GitHub][1].


Release
-------

This is the `xde-theme-aviation-1.1.5` package, released 2015-05-18.
This release, and the latest version, can be obtained from [GitHub][1],
using a command such as:

    $> git clone https://github.com/bbidulock/xde-theme-aviation.git

Please see the [RELEASE][3] and [NEWS][4] files for release notes and
history of user visible changes for the current version, and the
[ChangeLog][5] file for a more detailed history of implementation
changes.  The [TODO][6] file lists features not yet implemented and
other outstanding items.

Please see the [INSTALL][8] file for installation instructions.

When working from `git(1)`, please use this file.  An abbreviated
installation procedure that works for most applications appears below.

This release is published under CCPL:cc-by-nc-nd-3.0 (primarily because
the base styles used to develop these styles were licensed under this
license).
Please see the license in the file [COPYING][10].


Quick Start
-----------

The quickest and easiest way to get `xde-theme-aviation` up and
running is to run the following commands:

    $> git clone https://github.com/bbidulock/xde-theme-aviation.git
    $> cd xde-theme-aviation
    $> ./autogen.sh
    $> ./configure
    $> make
    $> make DESTDIR="$pkgdir" install

This will configure, compile and install `xde-theme-aviation` the
quickest.  For those who like to spend the extra 15 seconds reading
`./configure --help`, some compile time options can be turned on and off
before the build.

For general information on GNU's `./configure`, see the file
[INSTALL][8].


Prerequisites
-------------

This package needs the [`xde-styles`][11] package to be useful and also
requires the `xde-setbg(1)` program from the [`xde-ctools`][12] package.


Issues
------

Report issues on GitHub [here][2].


Samples
-------

Following are the six wallpapers included in the theme:

![aircanada_mountains.jpg](images/aircanada_mountains.jpg "Wallpaper #1")
![clouds.jpg](images/clouds.jpg "Wallpaper #2")
![greenland.jpg](images/greenland.jpg "Wallpaper #3")
![groundstation.jpg](images/groundstation.jpg "Wallpaper #4")
![skis.jpg](images/skis.jpg "Wallpaper #5")
![soaring.jpg](images/soaring.jpg "Wallpaper #6")



[1]: https://github.com/bbidulock/xde-theme-aviation
[2]: https://github.com/bbidulock/xde-theme-aviation/issues
[3]: https://github.com/bbidulock/xde-theme-aviation/blob/master/RELEASE
[4]: https://github.com/bbidulock/xde-theme-aviation/blob/master/NEWS
[5]: https://github.com/bbidulock/xde-theme-aviation/blob/master/ChangeLog
[6]: https://github.com/bbidulock/xde-theme-aviation/blob/master/TODO
[7]: https://github.com/bbidulock/xde-theme-aviation/blob/master/COMPLIANCE
[8]: https://github.com/bbidulock/xde-theme-aviation/blob/master/INSTALL
[9]: https://github.com/bbidulock/xde-theme-aviation/blob/master/LICENSE
[10]: https://github.com/bbidulock/xde-theme-aviation/blob/master/COPYING
[11]: https://github.com/bbidulock/xde-styles
[12]: https://github.com/bbidulock/xde-ctools

[ vim: set ft=markdown sw=4 tw=72 nocin nosi fo+=tcqlorn spell: ]: #