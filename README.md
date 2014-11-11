##Sooncoin 

http://www.SoonCoin.com


Copyright (c) 2009-2013 Bitcoin Developers

Copyright (c) 2013 Sooncoin Developers

Copyright (c) 2014 Sooncoin Developers

##What is SoonCoin?
````
SoonCoin is an experimental new digital currency that enables instant payments to
anyone, anywhere in the world. SoonCoin uses peer-to-peer technology to operate
with no central authority: managing transactions and issuing money are carried
out collectively by the network. SoonCoin is also the name of the open source
software which enables the use of this currency.

For more information, as well as an immediately useable, binary version of
the SoonCoin client sofware, see www.SoonCoin.com
````

##*NIX Build Instructions
Tested build on Ubuntu 12.X
Required packages:
````
ntp git build-essential libssl-dev libdb-dev libdb++-dev 
libboost-all-dev libqrencode-dev libcurl4-openssl-dev automake make
````
Debian 6:
````
ntp git build-essential libssl-dev libdb-dev libboost-all-dev 
libqrencode-dev libcurl4-openssl-dev automake make libdb4.8++-dev 4.8.30-2

````

##Build Info
````
git clone https://github.com/SoonCoin/SoonCoin.git
cd SoonCoin/src
make -f makefile.unix USE_UPNP=-

Output: sooncoind
````
For smaller RAM systems, you may need to create a swap file for systems to build. 
This usually happens with under 1GB RAM
UBUNTU:
````
sudo dd if=/dev/zero of=/swapfile bs=64M count=16
sudo mkswap /swapfile
sudo swapon /swapfile
````




````
##License
````
SoonCoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.
````
