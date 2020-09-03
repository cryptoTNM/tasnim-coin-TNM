Tasnimcoin integration/staging tree
================================

http://www.tasnimcoin.org

Copyright (c) 2009-2014 Bitcoin Developers
Copyright (c) 2011-2014 Tasnimcoin Developers

What is Tasnimcoin?
----------------

Tasnimcoin is a lite version of Bitcoin using scrypt as a proof-of-work algorithm.
 - 2.5 minute block targets
 - subsidy halves in 840k blocks (~4 years)
 - ~84 million total coins

The rest is the same as Bitcoin.
 - 50 coins per block
 - 2016 blocks to retarget difficulty

For more information, as well as an immediately useable, binary version of
the Tasnimcoin client sofware, see http://www.tasnimcoin.org.

License
-------

Tasnimcoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------

Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the Tasnimcoin
development team members simply pulls it.

If it is a *more complicated or potentially controversial* change, then the patch
submitter will be asked to start a discussion with the devs and community.

The patch will be accepted if there is broad consensus that it is a good thing.
Developers should expect to rework and resubmit patches if the code doesn't
match the project's coding conventions (see `doc/coding.txt`) or are
controversial.

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/tasnimcoin-project/tasnimcoin/tags) are created
regularly to indicate new official, stable release versions of Tasnimcoin.

Testing
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test. Please be patient and help out, and
remember this is a security-critical project where any mistake might cost people
lots of money.

### Automated Testing

Developers are strongly encouraged to write unit tests for new code, and to
submit new unit tests for old code.

Unit tests for the core code are in `src/test/`. To compile and run them:

    cd src; make -f makefile.unix test

Unit tests for the GUI code are in `src/qt/test/`. To compile and run them:
.   sudo apt-get install qt5-default
    qmake BITCOIN_QT_TEST=1 -o Makefile.test bitcoin-qt.pro
    make -f Makefile.test
    ./tasnimcoin-qt_test
    If you want to build the wallet on Ubuntu, do the following:

install dependencies
sudo apt-get update
sudo apt-get install qt5-default
sudo apt-get install build-essential libboost-all-dev libcurl4-openssl-dev libdb5.3-dev libdb5.3++-dev git qt-sdk libminiupnpc-dev libssl-dev

clone this repo
git clone https://github.com/cryptoTNM/tasnim-coin-TNM.git

build the wallet
qmake 
than//
make

#/add seed nodes (were not included in the source code)
in your home folder in .Funcoin, in home hidden file
create Funcoin.conf and add the following:

addnode=95.85.15.176

addnode=95.85.8.14
    

