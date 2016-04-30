Links2 for OpenWRT
==================

This is a quick hack, done to include the links2 browser into the
[OpenWRT](https://openwrt.org/) distribution.

Tested with 15.05.1.

To build the ipk-package get the SDK, unpack it, then do a
cd packages
git clone git://github.com/SvOlli/openwrt-links2.git links2
cd ..
make

