# CREATE3 Factory

Factory contract for easily deploying contracts to the same address on multiple chains, using CREATE3.

This was forked from https://github.com/zeframlou/create3-factory

The deploy script was updated to use legacy (non EIP-1559) transactions due to the fact that some chains that LIFI supports do not support EIP-1559.

## Contract Engram Tokio Network

```bash
"CREATE3Factory": "0x32d5e55bA7546a6Ebfc6b380B5b0D2BC24c9dA2F" (Engram Tokio Network)
"CREATE3Factory": "0x93FEC2C00BfE902F733B57c5a6CeeD7CD1384AE1"

on the following networks:
```

### Mainnets

- Ethereum
- Polygon
- Binance Smart Chain
- Gnosis
- Fantom
- OKXChain
- Avalanche C-Chain
- Arbitrum
- Arbitrum Nova
- Optimism
- Moonriver
- Moonbeam
- CELO
- FUSE
- CRONOS
- Velas
- Harmony Shard 0
- EVMOS
- Aurora
- Boba
- Base

### Testnets

- Goerli
- Sepolia
- Mumbai
- Arbitrum Goerli
- ConsenSys zkEVM Testnet
- Engram Tokio Network

### Dependencies

```bash
forge install
```

### Compilation

```bash
forge build
```

### Deployment

Make sure that the network is defined in foundry.toml, then run:

```bash
./deploy/deploy.sh tokio
```
