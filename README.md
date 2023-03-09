Welcome to MetaViral Blockchain

---
## Getting Started

Prior to using go install make sure that you have Go >=1.18 installed and properly configured.

The stable branch is the branch of the latest release.

```
git clone https://github.com/0xPolygon/polygon-edge.git
cd polygon-edge/
go build -o polygon-edge main.go
sudo mv polygon-edge /usr/local/bin
```

## Genesis

Genesis file can get here: https://github.com/MetaViralBit/Genesis


## Staking

Staking contract can find here

```https://github.com/MetaViralBit/MetaViral-Staking-Contract/blob/master/contracts/Staking.sol```

Step to staking
1. Clone repo: https://github.com/MetaViralBit/MetaViral-Staking-Contract

```
git clone https://github.com/MetaViralBit/MetaViral-Staking-Contract.git
```

3. Create env from env.example

```
cp env.example env
```

4. Update validator private key, BLS key

```JSONRPC_URL=https://mainnet-rpc.metaviralscan.com
PRIVATE_KEYS=YOUR_NODE_VALIDATOR_PRIVATE_KEY
BLS_PUBLIC_KEY=YOUR_NODE_VALIDATOR_BLS_KEY
STAKING_CONTRACT_ADDRESS=0x0000000000000000000000000000000000001001
MAX_VALIDATOR_COUNT=1000
MIN_VALIDATOR_COUNT=3
```
5. Run stake

```$ npm run stake```


## Working with node

See more detail guide here: https://wiki.polygon.technology/docs/edge/get-started/set-up-ibft-on-the-cloud

---

Copyright 2022 MetaViral

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
