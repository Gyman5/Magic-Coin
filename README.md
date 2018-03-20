# Magic The League Coin

Algo: Scrypt POS/POW
RPC port 18835
P2P port 18836
Block reward 1 coin
Max coin supply 450,000,000 coins
Premine percent 20%
PoS percentage 35% per year
Last PoW block block 50,000
Coinbase maturity 5 blocks
Target spacing 1 minute
Target timespan 1 block
Transaction confirmations 4 blocks


Preparation Build Qt-Wallet on OSX
-----------

Install the OS X command line tools:

`xcode-select --install`

When the popup appears, click `Install`.

Then install [Homebrew](https://brew.sh).

Dependencies
----------------------

<<<<<<< HEAD
brew install qt5 automake berkeley-db4 libtool boost miniupnpc openssl pkg-config protobuf python3 qt libevent
=======
brew install qt5 automake berkeley-db4 libtool boost miniupnpc openssl pkg-config protobuf python3 libevent
>>>>>>> fb3099b6d3f92cd331cc007c336c8872f5f85f9b


Compiling
----------------------

git clone https://github.com/mad345/Magic-Coin.git

cd Magic-Coin

qmake Magic-qt-mac.pro

make


Notes
-----

* Tested on OS X 10.8 through 10.13 on 64-bit Intel processors only.

* check your qt,bdb,boost,upnp version in the /usr/local/Cellar/ directory

