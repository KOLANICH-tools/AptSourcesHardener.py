AptSourcesHardener.py [![Unlicensed work](https://raw.githubusercontent.com/unlicense/unlicense.org/master/static/favicon.png)](https://unlicense.org/)
===============
![GitLab Build Status](https://gitlab.com/KOLANICH/AptSourcesHardener.py/badges/master/pipeline.svg)
[![TravisCI Build Status](https://travis-ci.org/KOLANICH/AptSourcesHardener.py.svg?branch=master)](https://travis-ci.org/KOLANICH/AptSourcesHardener.py)
![GitLab Coverage](https://gitlab.com/KOLANICH/AptSourcesHardener.py/badges/master/coverage.svg)
[![Coveralls Coverage](https://img.shields.io/coveralls/KOLANICH/AptSourcesHardener.py.svg)](https://coveralls.io/r/KOLANICH/AptSourcesHardener.py)
[![Libraries.io Status](https://img.shields.io/librariesio/github/KOLANICH/AptSourcesHardener.py.svg)](https://libraries.io/github/KOLANICH/AptSourcesHardener.py)

This is the library to harden `sources.lists` using the recommendations from https://wiki.debian.org/DebianRepository/UseThirdParty (for all the sources).

* Binds every source to its public key.
    * If a file is present, uses the file
    * Otherwise uses key fingerprint.

Requirements
------------
* [`AptSourcesList.py`](https://gitlab.com/KOLANICH/AptSourcesList.py) ![Licence](https://img.shields.io/github/license/KOLANICH/AptSourcesList.py.svg) [![PyPi Status](https://img.shields.io/pypi/v/AptSourcesList.svg)](https://pypi.python.org/pypi/AptSourcesList) [![TravisCI Build Status](https://travis-ci.org/KOLANICH/AptSourcesList.py.svg?branch=master)](https://travis-ci.org/KOLANICH/AptSourcesList.py) [![Libraries.io Status](https://img.shields.io/librariesio/github/KOLANICH/AptSourcesList.py.svg)](https://libraries.io/github/KOLANICH/AptSourcesList.py)
