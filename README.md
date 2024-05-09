## Bleap Setup
1. `git checkout releases/v0.7`
2. `yarn install`
3. `npx hardhat compile`
4. `yarn remove @nomiclabs/hardhat-etherscan`
5. `yarn add --save-dev @nomiclabs/hardhat-etherscan`
6. `npx hardhat verify --network dev 0x0000000071727De22E5E9d8BAf0edAc6f37da032 --show-stack-traces`


Implementation of contracts for [ERC-4337](https://eips.ethereum.org/EIPS/eip-4337) account abstraction via alternative mempool.

# Resources

[Vitalik's post on account abstraction without Ethereum protocol changes](https://medium.com/infinitism/erc-4337-account-abstraction-without-ethereum-protocol-changes-d75c9d94dc4a)

[Discord server](http://discord.gg/fbDyENb6Y9)

[Bundler reference implementation](https://github.com/eth-infinitism/bundler)

[Bundler specification test suite](https://github.com/eth-infinitism/bundler-spec-tests)
