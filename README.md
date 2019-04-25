# AndusChain Binary Download

AndusChain TestNet binary now version is 0.6.6-anduschain-unstable.

## Runing AndusChain Geth

if you see find geth option, type you command ```geth -h```.

geth --rpc --rpcaddr "0.0.0.0" --rpcport (customport) --rpccorsdomain "*" --verbosity 6 --rpcapi "admin, db, eth, debug, miner, net, shh, txpool, personal, web3" --port (customport) --clientPort (customport)

defaultInfo ( TEST NET )
- chainID : 1315
- networkID :102

defaultPort
- geth : 50505
- rpc : 8545
- fair client port : 50002

### WINDOWS
>windows/geth-windows-4.0-386-anduschain-0.6.7-20190425a.zip
- [Download] (https://github.com/anduschain/andusChainGethBinary/raw/master/windows/geth-windows-4.0-386-anduschain-0.6.7-20190425a.zip)
>windows/geth-windows-4.0-amd64-anduschain-0.6.7-20190425a.zip
- [Download] (https://github.com/anduschain/andusChainGethBinary/raw/master/windows/geth-windows-4.0-amd64-anduschain-0.6.7-20190425a.zip)

### MAC
>mac/geth-darwin-10.6-amd64-anduschain-0.6.7-20190425a.tar.gz
- [Download] (https://github.com/anduschain/andusChainGethBinary/raw/master/mac/geth-darwin-10.6-amd64-anduschain-0.6.7-20190425a.tar.gz)

#### LINUX
>linux/geth-linux-386-anduschain-0.6.7-20190425a.tar.gz
- [Download] (https://github.com/anduschain/andusChainGethBinary/raw/master/linux/geth-linux-386-anduschain-0.6.7-20190425a.tar.gz)
>linux/geth-linux-amd64-anduschain-0.6.7-20190425a.tar.gz
- [Download] (https://github.com/anduschain/andusChainGethBinary/raw/master/linux/geth-linux-amd64-anduschain-0.6.7-20190425a.tar.gz)

### STATIC-NODE.JSON
> static-node.json
- [Download] (https://github.com/anduschain/andusChainGethBinary/raw/master/staic-node.json)

static-node.json file should be located in datadir(default ~/.AndusChain)

static-node.json을 다운받아 datadir(기본 ~/.AndusChain)폴더에 지정해놓습니다.

Geth를 실행하면서 기본적으로 addPeer를 해놓아야 하는 노드들의 정보가 저장되어있습니다.



