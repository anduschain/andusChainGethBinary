# AndusChain Binary Download

AndusChain TestNet binary now version is 0.6.0-unstable.

## Runing AndusChain Geth

if you see find geth option, type you command ```geth -h```.

geth --rpc --rpcaddr "0.0.0.0" --rpcport (customport) --rpccorsdomain "*" --verbosity 6 --rpcapi "admin, db, eth, debug, miner, net, shh, txpool, personal, web3" --port (customport) --clientPort (customport)

defaultInfo
- chainID : 3355
- networkID :3355

defaultPort
- geth : 30303
- rpc : 8545
- fair client port : 50002

### WINDOWS
>windows/geth-windows-4.0-386-0.6.0-20190221a.zip
- [Download] (https://github.com/anduschain/andusChainGethBinary/raw/master/windows/geth-windows-4.0-386-0.6.0-20190221a.zip)
>windows/geth-windows-4.0-amd64-0.6.0-20190221a.zip
- [Download] (https://github.com/anduschain/andusChainGethBinary/raw/master/windows/geth-windows-4.0-amd64-0.6.0-20190221a.zip)

### MAC
>mac/geth-darwin-10.6-amd64-0.6.0-20190221a.tar.gz
- [Download] (https://github.com/anduschain/andusChainGethBinary/raw/master/mac/geth-darwin-10.6-amd64-0.6.0-20190221a.tar.gz)

#### LINUX
>linux/geth-linux-386-0.6.0-20190221a.tar.gz
- [Download] (https://github.com/anduschain/andusChainGethBinary/raw/master/linux/geth-linux-386-0.6.0-20190221a.tar.gz)
>linux/geth-linux-amd64-0.6.0-20190221a.tar.gz
- [Download] (https://github.com/anduschain/andusChainGethBinary/raw/master/linux/geth-linux-amd64-0.6.0-20190221a.tar.gz)
>linux/geth-linux-arm-5-0.6.0-20190221a.tar.gz
- [Download] (https://github.com/anduschain/andusChainGethBinary/raw/master/linux/geth-linux-arm-5-0.6.0-20190221a.tar.gz)
>linux/geth-linux-arm-6-0.6.0-20190221a.tar.gz
- [Download] (https://github.com/anduschain/andusChainGethBinary/raw/master/linux/geth-linux-arm-6-0.6.0-20190221a.tar.gz)
>linux/geth-linux-arm-7-0.6.0-20190221a.tar.gz
- [Download] (https://github.com/anduschain/andusChainGethBinary/raw/master/linux/geth-linux-arm-7-0.6.0-20190221a.tar.gz)
>linux/geth-linux-arm64-0.6.0-20190221a.tar.gz
- [Download] (https://github.com/anduschain/andusChainGethBinary/raw/master/linux/geth-linux-arm64-0.6.0-20190221a.tar.gz)
>linux/geth-linux-mips64-0.6.0-20190221a.tar.gz
- [Download] (https://github.com/anduschain/andusChainGethBinary/raw/master/)linux/geth-linux-mips64-0.6.0-20190221a.tar.gz
>linux/geth-linux-mips64le-0.6.0-20190221a.tar.gz
- [Download] (https://github.com/anduschain/andusChainGethBinary/raw/master/linux/geth-linux-mips64le-0.6.0-20190221a.tar.gz)

### STATIC-NODE.JSON
> static-node.json
- [Download] (https://github.com/anduschain/andusChainGethBinary/raw/master/staic-node.json)
static-node.json file should be located in datadir(default ~/.AndusChain)
static-node.json을 다운받아 datadir(기본 ~/.AndusChain)폴더에 지정해놓습니다.
Geth를 실행하면서 기본적으로 addPeer를 해놓아야 하는 노드들의 정보가 저장되어있습니다.



