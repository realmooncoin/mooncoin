# Mooncoin [MOON]
http://mooncoin.info/

![Mooncoin](http://bit.ly/moonlogo)

## What is Mooncoin?
Mooncoin is like Bitcoin, but based on Litecoin, and aimed to take you TO THE MOON!
http://mooncoin.info/

## IRC
irc.freenode.net Channel: #mooncoin

## License
Mooncoin is released under the terms of the MIT license. See [COPYING](COPYING)
for more information or see http://opensource.org/licenses/MIT.

## Development and Contributions
Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

## Frequently Asked Questions

### How many Mooncoins exist?
As of the time of this writing, approximately 27 billion moon have been issued. Sometime in the next five to seven years, there will be roughly 384,400,000,000 coins in existence, which is roughly one coin for every millimeter of distance from the Earth TO THE MOON!
For the block schedule, see http://en.wikipedia.org/wiki/Mooncoin#Block_schedule

### Mooncoin details
Scrypt Proof of Work

90 second block targets with Kimoto's Gravity Well to discipline the difficulty adjustments per block.

Random block rewards:

Blocks 1-100,000: 0-2,000,000 MOON
Blocks 100,001-200,000: 0-1,000,000 MOON
Blocks 200,001-250,000: 0-600,000 MOON
Blocks 250,001-300,000: 0-350,000 MOON
Blocks 300,001-350,000: 0-175,000 MOON
Blocks 350,001-375,000: 0-100,000 MOON
Blocks 375,001-384,400: 0-50,000 MOON

All future blocks are a fixed 29531 MOON.

### How to build Mooncoin

    sudo apt-get install build-essential \
                         libssl-dev \
                         libdb5.1++-dev \
                         libboost-all-dev \
                         libqrencode-dev \
                         libminiupnpc-dev

    cd src/
    make -f makefile.unix USE_UPNP=1 USE_IPV6=1 USE_QRCODE=1

### Ports
RPC 44663
P2P 44664
