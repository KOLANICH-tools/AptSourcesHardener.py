AptSourcesHardener.py [![Unlicensed work](https://raw.githubusercontent.com/unlicense/unlicense.org/master/static/favicon.png)](https://unlicense.org/)
===============
~~![GitLab Build Status](https://gitlab.com/KOLANICH/AptSourcesHardener.py/badges/master/pipeline.svg)~~
~~![GitLab Coverage](https://gitlab.com/KOLANICH/AptSourcesHardener.py/badges/master/coverage.svg)~~
[![Libraries.io Status](https://img.shields.io/librariesio/github/KOLANICH/AptSourcesHardener.py.svg)](https://libraries.io/github/KOLANICH/AptSourcesHardener.py)
[![Code style: antiflash](https://img.shields.io/badge/code%20style-antiflash-FFF.svg)](https://codeberg.org/KOLANICH-tools/antiflash.py)

**We have moved to https://codeberg.org/KOLANICH-tools/AptSourcesHardener.py, grab new versions there.**

Under the disguise of "better security" Micro$oft-owned GitHub has [discriminated users of 1FA passwords](https://github.blog/2023-03-09-raising-the-bar-for-software-security-github-2fa-begins-march-13/) while having commercial interest in success of [FIDO 1FA specifications](https://fidoalliance.org/specifications/download/) and [Windows Hello implementation](https://support.microsoft.com/en-us/windows/passkeys-in-windows-301c8944-5ea2-452b-9886-97e4d2ef4422) which [it promotes as a replacement for passwords](https://github.blog/2023-07-12-introducing-passwordless-authentication-on-github-com/). It will result in dire consequencies and is competely inacceptable, [read why](https://codeberg.org/KOLANICH/Fuck-GuanTEEnomo).

If you don't want to participate in harming yourself, it is recommended to follow the lead and migrate somewhere away of GitHub and Micro$oft. Here is [the list of alternatives and rationales to do it](https://github.com/orgs/community/discussions/49869). If they delete the discussion, there are certain well-known places where you can get a copy of it. [Read why you should also leave GitHub](https://codeberg.org/KOLANICH/Fuck-GuanTEEnomo).

---

This is the library to harden `sources.lists` using the recommendations from https://wiki.debian.org/DebianRepository/UseThirdParty (for all the sources).

* Binds every source to its public key.
    * If a file is present, uses the file
    * Otherwise uses key fingerprint.

Requirements
------------
* [`AptSourcesList.py`](https://codeberg.org/KOLANICH-libs/AptSourcesList.py) ![Licence](https://img.shields.io/github/license/KOLANICH/AptSourcesList.py.svg) [![PyPi Status](https://img.shields.io/pypi/v/AptSourcesList.svg)](https://pypi.python.org/pypi/AptSourcesList) [![Libraries.io Status](https://img.shields.io/librariesio/github/KOLANICH/AptSourcesList.py.svg)](https://libraries.io/github/KOLANICH/AptSourcesList.py)
