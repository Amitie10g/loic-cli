# LOIC -- Low Orbital Ion Cannon Load Tester (CLI implementation)

This is a fork of the [Emily Eisenberg](https://github.com/xymostech)'s [loic](https://github.com/xymostech/loic) project, a command line implementation of [LOIC (Low Orbital Ion Cannon Load Tester)](https://en.wikipedia.org/wiki/Low_Orbit_Ion_Cannon) written in [C](https://en.wikipedia.org/wiki/C_%28programming_language%29), forked specifically to provide releases for multiple platforms.

**For educaationaal purposes only**

## Usage
* ``loic <domain>`` (from Releases)

## Downloading
* Standalone executable is available at [Releases](https://github.com/amitie10g/loic-cli/releases/tag/20240411006)

## Building
* For your convenience, you can use the [GCC Docker container image](https://hub.docker.com/_/gcc)
  ```
  git clone https://github.com/Amitie10g/loic-cli.git
  cd loic-cli
  docker run -v $(pwd):/root -w /root gcc make
  ```
  The Makefile instructs to build a static ejecutable.

## For Windows
Just use the well-known [.NET-based LOIC](https://github.com/NewEraCracker/LOIC).

You need to edit the source code for replacing POSIX functions into win32 ones, then, compile with MinGW64 GCC as static executable.

## Why?
Just for fun

## License
Emily Eisenberg haven't added a license for her project. So, I licensed this fork under the MIT License.
