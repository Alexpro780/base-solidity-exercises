[README.md](https://github.com/user-attachments/files/23952652/README.md)
# Base Solidity Exercises

Built for **Base** — a collection of Solidity contracts inspired by the official Base developer exercises, deployed and tested on the Base Sepolia testnet (chainId **84532**).

This repository is part of my public on‑chain / open‑source activity as a Base builder.

- **Author:** [Alexpro780](https://github.com/Alexpro780)
- **Network:** Base Sepolia (84532) and Base Mainnet (8453)
- **Goal:** Learn smart‑contract development on Base and leave an indexable GitHub footprint for future Base ecosystem programs and potential retro‑drops.

## Contents

The `contracts/` folder contains small, focused examples:

1. `BasicMath.sol` – arithmetic with overflow / underflow checks.
2. `ControlStructures.sol` – `if`, `else if`, custom errors, and simple logic.
3. `EmployeeStorage.sol` – storage layout, getters and setters.
4. `FavoriteRecords.sol` – nested mappings and dynamic arrays.
5. `GarageManager.sol` – working with structs and arrays.
6. `InheritanceExercise.sol` – abstract contracts, inheritance, and composition.
7. `SillyStringUtils.sol` & `ImportsExercise.sol` – libraries and imports.
8. `ErrorTriageExercise.sol` – simple debugging style helpers.
9. `AddressBook.sol` & `AddressBookFactory.sol` – contract factory with `new` keyword.
10. `UnburnableToken.sol` – minimal claimable token without burn.
11. `WeightedVoting.sol` – ERC‑20 style voting with weights.
12. `HaikuNFT.sol` – simple ERC‑721 example for “Haiku” NFTs.

All contracts are written in Solidity ^0.8.x so they include automatic overflow checks and are easy to experiment with in Remix or Foundry.
