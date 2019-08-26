AptSourcesHardener.py [![Unlicensed work](https://raw.githubusercontent.com/unlicense/unlicense.org/master/static/favicon.png)](https://unlicense.org/)
===============
~~![GitLab Build Status](https://gitlab.com/KOLANICH/AptSourcesHardener.py/badges/master/pipeline.svg)~~
~~![GitLab Coverage](https://gitlab.com/KOLANICH/AptSourcesHardener.py/badges/master/coverage.svg)~~
[![Libraries.io Status](https://img.shields.io/librariesio/github/KOLANICH/AptSourcesHardener.py.svg)](https://libraries.io/github/KOLANICH/AptSourcesHardener.py)
[![Code style: antiflash](https://img.shields.io/badge/code%20style-antiflash-FFF.svg)](https://codeberg.org/KOLANICH-tools/antiflash.py)

This is the library to harden `sources.lists` using the recommendations from https://wiki.debian.org/DebianRepository/UseThirdParty (for all the sources).

* Binds every source to its public key.
    * If a file is present, uses the file
    * Otherwise uses key fingerprint.

Requirements
------------
* [`AptSourcesList.py`](https://codeberg.org/KOLANICH-libs/AptSourcesList.py) ![Licence](https://img.shields.io/github/license/KOLANICH/AptSourcesList.py.svg) [![PyPi Status](https://img.shields.io/pypi/v/AptSourcesList.svg)](https://pypi.python.org/pypi/AptSourcesList) [![Libraries.io Status](https://img.shields.io/librariesio/github/KOLANICH/AptSourcesList.py.svg)](https://libraries.io/github/KOLANICH/AptSourcesList.py)
