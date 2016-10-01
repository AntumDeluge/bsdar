## The AR Archiver

This is the FreeBSD variant of [the ar archiver](https://en.wikipedia.org/wiki/Ar_(Unix)).

The intention behind this fork is to create a portable alternative to [dpkg](https://en.wikipedia.org/wiki/Dpkg) for use with [Debreate](https://github.com/AntumDeluge/debreate). This would allow using Debreate to create .deb packages on platforms that do not supply the Debian packager.

The reasoning behind using the BSD variant over GNU is that archives produced with it are compatible with those of dpkg, while GNU's are not (citation needed).

This has been forked from [FreeBSD's HEAD Subversion repository](http://svn.freebsd.org/base/head/usr.bin/ar/) ([revision 301974](https://svnweb.freebsd.org/base/head/usr.bin/ar/?pathrev=301974)).