Cyberyen Core version 0.21.2.5 is now available from:

 <https://download.cyberyen.org/cyberyen-0.21.2.5/>.

This is a new patch version release that includes important security updates. Fix block subsidy calculations.

Please report bugs using the issue tracker at GitHub:

  <https://github.com/cyberyen/cyberyen/issues>

To receive security and update notifications, please subscribe to:

  <https://matrix.to/#/#cyberyen-dev:matrix.org>

Notable changes
===============

Important Security Updates
--------------------------

This release contains fixes that harden node and network security. These fixes are very important for every node operator and wallet user.

Fix Difficulty Calculations
---------------

Implementation of the Lwma3CalculateNextWorkRequired2 retargeter algorithm at block 175000 to maintain network stability and prevent freezes by increasing the window size.


Credits
=======

Thanks to everyone who directly contributed to this release:

- [The Bitcoin Core Developers](https://github.com/bitcoin/bitcoin/tree/master/doc/release-notes)
- [The Litecoin Core Developers](https://github.com/litecoin-project/litecoin/tree/master/doc/release-notes)
- [teh Cyberyen Core](https://github.com/cyberyen/cyberyen/tree/master/doc/release-notes)
