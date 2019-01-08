# Kriegerrand-Blockchain-Explorer
Block explorer for Kriegerrand CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon MindBraind. It should be accessible from the Internet. Run MindBraind with open port as follows:
```bash
./MindBraind --enable-cors="*" --enable-blockexplorer --rpc-bind-ip=0.0.0.0 --rpc-bind-port=11898
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.


### Note
This is a fork of TurtleCoin Explorer turtlecoin/turtle-explorer-js
A lot of this code is from the great Karbovanets/Karbowanec-Blockchain-Explorer
