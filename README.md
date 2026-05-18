[![Mentioned in Awesome Foundry](https://awesome.re/mentioned-badge-flat.svg)](https://github.com/crisgarner/awesome-foundry)

# Diamond-2535-Lossless-Auction

A modular NFT auction marketplace built using the EIP-2535 Diamond Standard with Hardhat and Foundry.

This project explores upgradeable smart contract architecture using Diamonds while implementing auction mechanics for NFTs in a scalable and maintainable way.

One of the core ideas behind this project was understanding how complex Solidity systems can be broken into reusable facets while maintaining upgradeability and clean contract organization.

---

## Features

* EIP-2535 Diamond architecture
* Modular facet-based smart contracts
* NFT auction functionality
* Upgradeable and extensible system design
* Hardhat + Foundry development workflow
* Solidity custom errors for easier debugging

---

## Tech Stack

* Solidity
* Hardhat
* Foundry
* Ethers.js
* OpenZeppelin Contracts

---

## Project Structure

```bash id="af2j3"
contracts/
 ├── Diamond.sol
 ├── facets/
 ├── interfaces/
 ├── libraries/
 └── upgradeInitializers/

scripts/
test/
```

---

## Installation

Clone the repository:

```bash id="0u3dj"
git clone https://github.com/IjayAbby/Diamond-2535-Lossless-Auction.git
```

Install dependencies:

```bash id="b3j4q"
yarn && forge update
```

---

## Compile Contracts

```bash id="m8wq2"
npx hardhat compile
```

---

## Run Tests

### Foundry

```bash id="j7sn1"
forge test
```

### Hardhat

```bash id="w92la"
npx hardhat test
```

---

## Deployment

### Hardhat

```bash id="r8m2p"
npx hardhat run scripts/deploy.js
```

---

## Notes

A lot of improvements are still being explored, especially around:

* gas optimization
* advanced auction logic
* frontend integration
* additional security testing
* developer tooling improvements

Contributions, ideas, and feedback are always welcome.

---

## Bonus

The `DiamondLoupeFacet` uses an updated `LibDiamond` implementation that leverages Solidity custom errors to improve debugging and upgrade transparency when working with Diamonds.

This project was also part of my deeper exploration into:

* upgradeable protocol architecture
* advanced Solidity patterns
* smart contract modularity
* developer tooling and testing workflows

---

## References

* EIP-2535 Diamond Standard
* Hardhat Documentation
* Foundry Book

---

## Author

Ijay Abby

LinkedIn:
[Profile](https://www.linkedin.com/in/ijayabby4)
