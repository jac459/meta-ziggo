 # meta-ziggo
 # The files in this repository are developed to support the Dutch Ziggo-signals being controlled by NEEO remotes runn9ng the .metadriver solution.

## Description of repository
Ziggo, a large dutch cable-tv provider distributes a number of set-top boxes to provide Cable-TV to their customers
As Ziggo is part of Liberty Global, the same strategy is used in more countries than The Netherlands alone.
Ziggo currently has two mainstream type of devices for their set-top boxes:
- Horizonbox (Samsung GW-7400 / GW-7401)
- Next (Arris DCX960)

The Horizonbox is the classic box, the Next is the current box.
Currently, the device drivers in this package support the Horizonbox.
However, a version that suports the Ziggo Next is available, but is too complex at this moment (in my opinion).
It will be reworked once I'm able to test with a Ziggo next.

# Installation
The driver requires no additional packages, it can be installed through the metadrivers APP on NEEO-remote, and can be found under Library as an External driver. 

The work on thios driver was very inspired BY Gilles vd Hoven's Horizonbox-driver for NEEO.
 # Errors, Bugs, shortcomings #
1) Shortcoming: no discovery of boxes, IP-address needs to be provided manually
2) The handshaking with the Horizonbox works fine taking in practice 2 stages of authentication, though other examples of this driver (Gilles van der Hoven) have defined 4 stages. 