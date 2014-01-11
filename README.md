# Scarcoin [SCAR]
http://scarcoin.com/

## What is ScarCoin? - 
Scarcoin is like Bitcoin, but based on Litecoin.
http://scarcoin.com/

## License - Much license
DogeCoin is released under the terms of the MIT license. See [COPYING](COPYING)
for more information or see http://opensource.org/licenses/MIT.

## Development and contributions - omg developers
Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

## Very Much Frequently Asked Questions

### How much scarcoins can exist?
Total of 200,000,000,000 much coins

### How to get scarcoins?
Scrypt Proof of Work

45 second Block Targets, 3 Hour Diff Readjustments

Special reward system: Random block rewards

1-100,000: 0-1,000,000 Scarcoin Reward

100,001 — 200,000: 0-1,000,000 Scarcoin Reward
200,001 — 300,000: 0-500,000 Scarcoin Reward
300,001 — 400,000: 0-250,000 Scarcoin Reward
400,001 — 500,000: 0-125,000 Scarcoin Reward
500,001 - 600,000: 0-62,500 Scarcoin Reward
600,000+ — 10,000 Reward (flat)

### make scarcoind

    sudo apt-get install build-essential \
                         libssl-dev \
                         libdb5.1++-dev \
                         libboost-all-dev \
                         libqrencode-dev \
                         libminiupnpc-dev

    cd src/
    make -f makefile.unix USE_UPNP=1 USE_IPV6=1 USE_QRCODE=1

### ports
RPC 22444
P2P 22445

