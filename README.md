Carbon Footprint for Google Maps
================================

A browser extension that displays carbon footprint information in multiple map services.

Building and using
------------------

* clone this repository

* run `npm install`

* run `gulp group` or `gulp groupFirefox` or `gulp groupChrome` or `gulp groupSafari`

* add flag `--minify` to minify the build. This includes removing of all debug statements and comments.

* for chrome, load the unpacked extension from the Build/Chrome folder

* for firefox, run `jpm runFirefox` and use the -b flag to point to a non extension veryifying version of Firefox like the Developer Edition

* for safari, load folder with extension `.safariextension` into _Extension Builder_ `Develop -> Show Extension Builder`. To show _Develop_ menu go to `Safari -> Preferences -> Advanced`. Change extension metadata as required from the _Extension Builder_. To package the extension for distribution, get an extension certificate from Apple.

Licenses
--------

* GNU-GPL-3.0

* CC-By-NC-ND [![License](https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-nd/4.0/)


Contributions
-------------

If you would like to contribute to the development of this extension, please [contact the developers](mailto:bruno.wp@gmail.com).

* [Google Summer of Code](GoogleSummerOfCode.md) grants are available every year. If you would like to apply, it is never too early to contact us. 
