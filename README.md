# TON Smartcontracts development

1. install deps:
```bash
yarn install
```
2. create compiled file:
```bash
mkdir build && touch build/main.compiled.json
```
2. compile contract:
```bash
yarn compile
```
3. deploy contract
```bash
yarn deploy         # testnet
yarn deploy:mainnet # mainnet
```
