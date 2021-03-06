PvPGN Magic Builder
=====
PvPGN Magic Builder gives you an easy way to build your own PvPGN binaries from the latest
source code for Windows.

Let's see how it works in one-minute video: http://www.youtube.com/watch?v=70KYeFqG34M

[![PvPGN Builder](http://i.imgur.com/7VVSjji.png)](http://i.imgur.com/ySKCB8G.png) [![D2GS Builder](http://i.imgur.com/c5YaCs3.png)](http://i.imgur.com/0ezOHmm.png)



_*Note: use [Development Kit](https://github.com/pvpgn/pvpgn-magic-builder/releases/tag/pvpgn-dev-kit) to modify and debug your source code.*_
 
Features
--
 * Builds a [PvPGN](https://github.com/pvpgn/pvpgn-server) with one of the databases support: [MySQL](http://wikipedia.org/wiki/MySQL), [PostgreSQL](http://wikipedia.org/wiki/PostgreSQL), [SQLite3](http://wikipedia.org/wiki/SQLite) or [ODBC](http://wikipedia.org/wiki/Open_Database_Connectivity). Feature to enable [Lua](http://en.wikipedia.org/wiki/Lua_(programming_language)) scripting
 * Builds any version of [D2GS](http://harpywar.com/?a=articles&b=2&c=2&d=21), feature to download all DLL and MPQ that are necessary to start your server
 * Doesn’t require additional files - all built in
 * Has a multilanguage command line interface: Russian, English, Dutch, German, Polish, Serbian, Spanish, Ukrainian (please, translate [this file](https://github.com/pvpgn/pvpgn-magic-builder/blob/master/module/i18n/ENU.bat) if you know others)
 * (optional) [Auto updates](https://code.google.com/p/pvpgn-magic-builder/wiki/AutoUpdate)
 * (optional) Auto downloads actual PvPGN source code from the GIT
 * Auto configurates and compilates PvPGN source code
 * Auto create `release\` directory with a PvPGN binaries and support files that are ready to use immediately

Requirements
--
 * Visual C++ 2015 (Community is supported)

"Community" is the light edition of Visual Studio. It's free to [download](http://www.microsoft.com/visualstudio/downloads)
setup

*Note: Visual Studio 2015 doesn't install C++ by default. If you already have it installed then you have to rerun the setup, select `Modify` and then check `Programming Language -> C++`.*

*Without C++ installed Magic Builder throws an error `The CXX compiler identification is unknown`*


Downloads
--
Go to [Release](https://github.com/pvpgn/pvpgn-magic-builder/releases) section and download the latest release.


Discussions
--
 * (Русский) http://forums.harpywar.com/viewtopic.php?id=448
 * (English) http://forums.pvpgn.org/index.php?topic=4460
