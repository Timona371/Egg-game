## Egg-game

## About the project
EggHuntGame is a gamified NFT experience where participants search for hidden eggs to mint unique Eggstravaganza Egg NFTs. Players engage in an interactive hunt during a designated game period, and successful egg finds can be deposited into a secure Egg Vault.

## Scope (contracts)

The following contracts are included in the project:

```
src/
├── EggHuntGame.sol - Main game contract
└── EggstravaganzaNFT.sol - ERC20 token awarded to winners
└──EggVault.sol -Ownable contract
```

## Usage



## Compatibilities

**Blockchains:**

- Ethereum Mainnet
- All EVM-compatible chains

### Build

```bash
# Install dependencies
forge install OpenZeppelin/openzeppelin-contracts

# Build contracts
forge build
```

### Test

```bash
# Run all tests
forge test

# Run tests with gas reporting
forge test --gas-report
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```


### Deploy

```bash
# Deploy to local network
forge script scripts/Deploy.s.sol --rpc-url http://localhost:8545 --broadcast

# Deploy to testnet (example for Goerli)
forge script scripts/Deploy.s.sol --rpc-url $GOERLI_RPC_URL --private-key $PRIVATE_KEY --broadcast --verify --etherscan-api-key $ETHERSCAN_API_KEY
```

[//]: # (getting-started-close)

[//]: # (known-issues-open)

