Legocoin 
================================

Copyright (c) 2009-2013 Bitcoin Developers
Copyright (c) 2011-2013 Litecoin Developers
Copyright (c) 2013-2014 Dogecoin Developers

What is Legocoin?
----------------

Legocoin is a mish-mash of Litecoin, Dogecoin, and some new code I wrote.  It was created solely for fun and to demonstrate various new features that I have developed, such as the ability to snap a region of your desktop containing a QR image and converting it to a Legocoin address or private key for importing into a wallet.

The mining algorithm is super easy so you can create coins very quickly running in testnet.

Building
--------

I have built and tested Legocoin on Windows, Mac OS X 10.9.2, and Ubuntu.  I prefer to develop on Windows using VS2013 but I have been using a Qt .pro file for Mac and Linux.  You may need to modify the .pro file for your specific environment if you plan to use it.

The MSVC directory contains the Visual Studio 2013 project files to build the Qt exe, the daemon, and some other test programs that are part of the solution.  I also have a directory called build-helpers which contains batch files to help you build all the dependent libraries, including the ZebraCrossing library.

License
-------

Legocoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.



