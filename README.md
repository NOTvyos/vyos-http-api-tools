[//]: # (DISCLAIMER tE4AWE_AQahaxUGUpugu BEGIN)

> [!CAUTION]
> This project is an **independent fork of VyOS®**.
> It is **not affiliated with, endorsed by, or sponsored by VyOS Networks Corporation** by any means.
> VyOS® is a registered trademark of VyOS Networks Corporation.

[//]: # (DISCLAIMER tE4AWE_AQahaxUGUpugu END)

# vyos-http-api-tools
Debian files for wrapping FastAPI and supporting tools as a deb package, using dh_virtualenv

To build:

    dpkg-buildpackage -uc -us -tc -b

To update dependency versions from un-versioned packages names:
(Install pip-compile from 'pip-tools')

    pip-compile requirements.in > requirements.txt
