Sage
====

Sage is a Cygwin package manager. It includes a command-line installer for
Cygwin which cooperates with Cygwin Setup and uses the same repository.

[![bountysource][2]][1]

[1]:https://www.bountysource.com/teams/svnpenn
[2]:https://api.bountysource.com/badge/team?team_id=114003&style=raised

Operations
----------

~~~
install
  Install package(s).

remove
  Remove package(s) from the system.

update
  Download a fresh copy of the master package list (setup.ini) from the
  server defined in setup.rc.

download
  Retrieve package(s) from the server, but do not install/upgrade anything.

show
  Display information on given package(s).

depends
  Produce a dependency tree for a package.

rdepends
  Produce a tree of packages that depend on the named package.

list
  Search each locally-installed package for names that match regexp. If no
  package names are provided in the command line, all installed packages will
  be queried.

listall
  This will search each package in the master package list (setup.ini) for
  names that match regexp.

category
  Display all packages that are members of a named category.

listfiles
  List all files owned by a given package. Multiple packages can be specified
  on the command line.

search
  Search for downloaded packages that own the specified file(s). The path can
  be relative or absolute, and one or more files can be specified.

searchall
  Search cygwin.com to retrieve file information about packages. The provided
  target is considered to be a filename and searchall will return the
  package(s) which contain this file.
~~~

Quick start
-----------

Sage is a simple script. To install:

    lynx -source rawgit.com/svnpenn/sage/master/sage > sage
    install sage /bin

Example use of Sage:

    sage install nano
