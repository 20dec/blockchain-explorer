# BlackRose-Blockchain-Explorer
Block explorer for BlackRose CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon blackrosed. It should be accessible from the Internet. Run karbowanecd with open port as follows:
```bash
./blackrosed --restricted-rpc --enable-cors=* --enable-blockchain-indexes --rpc-bind-ip=0.0.0.0 --rpc-bind-port=2018
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.
