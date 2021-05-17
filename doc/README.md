Villanocoin Core
=============

Setup
---------------------
Villanocoin Core is the original Villanocoin client and it builds the backbone of the network. It downloads and, by default, stores the entire history of Villanocoin transactions, which requires approximately 22 gigabytes of disk space. Depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download Villanocoin Core, visit [villanocoin.org](https://villanocoin.org/).

Running
---------------------
The following are some helpful notes on how to run Villanocoin Core on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/villanocoin-qt` (GUI) or
- `bin/villanocoind` (headless)

### Windows

Unpack the files into a directory, and then run villanocoin-qt.exe.

### macOS

Drag Villanocoin Core to your applications folder, and then run Villanocoin Core.

### Need Help?

* See the documentation at the [Villanocoin Wiki](https://villanocoin.info/)
for help and more information.
* Ask for help on [#villanocoin](http://webchat.freenode.net?channels=villanocoin) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=villanocoin).
* Ask for help on the [VillanocoinTalk](https://villanocointalk.io/) forums, in the [Technical Support section](https://villanocointalk.io/c/technical-support).

Building
---------------------
The following are developer notes on how to build Villanocoin Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [macOS Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [FreeBSD Build Notes](build-freebsd.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [NetBSD Build Notes](build-netbsd.md)
- [Gitian Building Guide (External Link)](https://github.com/bitcoin-core/docs/blob/master/gitian-building.md)

Development
---------------------
The Villanocoin repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Productivity Notes](productivity.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [JSON-RPC Interface](JSON-RPC-interface.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [VillanocoinTalk](https://villanocointalk.io/) forums.
* Discuss general Villanocoin development on #villanocoin-dev on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=villanocoin-dev.

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [bitcoin.conf Configuration File](bitcoin-conf.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)
- [PSBT support](psbt.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
