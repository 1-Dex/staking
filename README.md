# Crosschain Staking Solidity Code

This Solidity smart contract enables crosschain staking, allowing users to deposit tokens and receive rewards. The staker can specify a beneficiary address, and only they can withdraw staked tokens. Beneficiaries can withdraw rewards.

## Compatibility with Connected Chains

For simplicity, this contract is designed to work with one connected chain at a time. The chain ID should be provided during deployment.

## Getting Started

1. Deploy the contract on a compatible chain using the provided chain ID.
2. Stakers can deposit tokens and specify a beneficiary address.
3. Stakers can withdraw their staked tokens when needed.
4. Beneficiaries can withdraw rewards.

### How To Use

Set Beneficiary Address:

```
npx hardhat set-beneficiary ADDRESS --contract ADDRESS --network goerli_testnet
```

Set Withdraw Address:

```
npx hardhat set-withdraw --contract ADDRESS --network goerli_testnet
```

Stake Tokens:

```
npx hardhat stake --amount 0.1 --contract ADDRESS --network goerli_testnet
```

Unstake Tokens:

```
npx hardhat unstake --contract ADDRESS --network goerli_testnet
```

## About ZetaChain

ZetaChain is a foundational, public blockchain designed to support generic smart contracts and messaging between any blockchain. It aims to open the crypto and global financial ecosystem to anyone, enabling fluid, multi-chain interactions.

## License and Disclaimer

Please review the license before using this code. Use it at your own risk. The authors are not responsible for any loss or damage.

```

```
