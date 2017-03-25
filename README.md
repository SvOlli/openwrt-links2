Links2 for OpenWRT
==================

This is a quick hack, done to include the links2 browser into the
[OpenWRT](https://openwrt.org/) distribution.

Tested with 15.05.1.

To build the ipk-package get the SDK, unpack it, then do a
```
cd package
git clone git://github.com/SvOlli/openwrt-links2.git links2
cd ..
make
```
Also make sure that the following options are enabled in the SDK:
  * Libraries ---> Compression ---> libbz2
  * Libraries ---> SSL ---> libopenssl
  * Libraries ---> libevent2
  * Libraries ---> zlib

If anyone would like to include this in the official distribution,
I'd be happy.
