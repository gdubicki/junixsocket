# THIS REPO IS VERY OUTDATED. DO NOT USE

Check out other junixsocket forks instead. For the ones I currently recommend see: http://stackoverflow.com/a/42874384/2693875

---


# junixsocket "pre-1.4" fork


## Purpose

This fork has been made to update junixsocket for https://github.com/grzegorz-dubicki/jedis/tree/2.1.0-with-unix-sockets project.

## Changes from original v. 1.3

* Using pre-1.4 codebase
* Updated to Java 1.6
* Minor fixes to make build process easier


## Status

*Building and tests passing, but not (yet) tested in production!*

## Building

Requirements, or rather: tested & working on:

* Ubuntu 12.04 LTS 64-bit with gcc 4.6.3 and glibc 2.15,
* Oracle JDK 1.6.0_45 64-bit *from PPA - http://www.webupd8.org/2012/11/oracle-sun-java-6-installer-available.html*
* Apache Ant 1.9.3 *from .tar.gz - http://ant.apache.org/bindownload.cgi*

How-to:

1. Install JDK 1.6 & set JAVA_HOME
2. Download Ant, unpack and set ANT_HOME to its dir & add $ANT_HOME/bin to PATH
3. Install some basic linux native compiling tools - gcc, g++, make etc.
4. Build with `ant -Dskip32=true` . This should end with "BUILD SUCCESSFUL".
5. Find built JARs in ./build dir.

## Upstream source

* SVN - http://junixsocket.googlecode.com/svn/trunk/

## Thanks

Thanks to:

* [Dr Christian Kohlschütter](http://www.kohlschutter.com/en/), author of junixsocket
* [Piotr Gabryjeluk](http://piotr.gabryjeluk.pl), author of http://svn2github.com/ tool

