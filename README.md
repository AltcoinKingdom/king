##kingdomcoin

kingdomcoin is x13 PoW/PoS cryptocurrency.

kingdomcoin – X13 CryptoCurrency
* RPC Port: 51990
* P2P Port: 50990
* Algorithm: X13 POW/POS starts on block 15,000
* Ticker: KING
* Max PoW Coins: Approximately 2.5 million
* 2.5% PoS Annual Interest

Block Reward Schedule
* 60 second blocks
* Block 0-100 are low reward (0)
* PoW Ends on Block 20160 (approx. 14 days)
* MinStakeAge: 2.5 hours
* Max: Unlimited

##Troubleshooting

In the event you encounter problems compiling the daemon, feel free to consult the guide below:

Receive the following error?

------------------------------------------

PROBLEM:

g++: error: .../src/leveldb/libleveldb.a: No such file or directory
g++: error: .../src/leveldb/libmemenv.a: No such file or directory

SOLUTION:

cd src/leveldb
make libleveldb.a libmemenv.a

CD back to src and try to build it again.

------------------------------------------


