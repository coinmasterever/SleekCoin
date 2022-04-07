SleekCoin
===========

What is SleekCoin
--------------
SleekCoin is a new crypto currency which is forked from Zcash, the project is stil under development.

## Prerequisites

### Recommended environment

Our recommendation is Ubuntu distribution

### Dependencies

Please install the following before building the project

```
    sudo apt-get install git make binutils curl gobjc++ libncurses5 autotools-dev automake libtool python pip
    sudo apt-get install libsasl2-dev python-dev libldap2-dev libssl-dev
    pip install pyOpenSSL secrets
```

## Getting Started

### Need Help?

* :speech_balloon: Join our community on [Discord](https://discordapp.com/invite/******)

### Latest stable branch

Checkout the latest stable branch

```
git checkout v4.6.0-2
```

### Create your own testnet

#### Configure your node

Create new configuration file

```
mkdir -p ~/.zcash
touch ~/.zcash/zcash.conf
```

#### Build the node

Build SleekCoin along with most dependencies (will be downloaded during the build process) from source by running the following command:

```
./zcutil/build.sh -j$(nproc)
```

Clean previous builds by running the following command:


```
 ./zcutil/clean.sh
```

License
-------

For license information see the file [COPYING](COPYING).
