# BytespeicherTrayIcon ![alt text](res/open-32.png "BytespeicherTrayIcon")
[![Build Status](https://travis-ci.org/Bytespeicher/BytespeicherTrayIcon.svg?branch=master)](https://travis-ci.org/Bytespeicher/BytespeicherTrayIcon) [![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FBytespeicher%2FBytespeicherTrayIcon.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2FBytespeicher%2FBytespeicherTrayIcon?ref=badge_shield)
 [![Build status](https://ci.appveyor.com/api/projects/status/rltl3xgwt914vvrk/branch/master?svg=true)](https://ci.appveyor.com/project/mkzero/bytespeichertrayicon/branch/master)


An application to show the opening status of the bytespeicher in the
system tray icon.

Tested:
 * Qt 5.7.1 on Windows 10
 * Qt 5.5.1 on Linux Mint
 * Qt 5.9.0 on Linux Mint
 * Qt 5.9.1 on Linux Mint
 
Dependencies:
 * Qt >= 4.2 (http://qt.nokia.com)
 * A C++ build system (GCC/GNU make or MS Visual C++ Express will do)

Compiling:
  qmake main.pro && make
or, if you are using MS Visual C++:
  qmake main.pro && nmake

By default, a notification is shown when the opening status changes. If you do
not want that, you can start the program with the --silent or -s option.

Windows compatibility has not yet been tested by me, though some users report
that it works too.

Versioning Scheme:
The version number is calculated by the formula 1-1/(2^n), where n is
incremented with each release. This way, the version number approaches 1 as n
approaches infinity.


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FBytespeicher%2FBytespeicherTrayIcon.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FBytespeicher%2FBytespeicherTrayIcon?ref=badge_large)