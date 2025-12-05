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

## How to Use (very simple)

You do **not** need to be a professional developer to use this repo.

### Option 1 — Just keep it on GitHub

1. Upload this folder to a new public repository called, for example, `base-solidity-exercises`.
2. Make sure the repository is **Public**.
3. Confirm that your GitHub account shows your email publicly and matches the email used for your Git commits.
4. That’s it — analytics tools (like Electric Capital) can already see this repo as part of your developer activity.

### Option 2 — Try deploying a contract on Base Sepolia

If you want to go a bit further:

1. Open <https://remix.ethereum.org> in your browser.
2. Create a new file and copy‑paste one of the contracts from `contracts/`.
3. In your wallet (MetaMask, Rabby, etc.) add **Base Sepolia** and get some test ETH from a faucet.
4. In Remix:
   - Select the Solidity compiler (0.8.x).
   - Compile the contract.
   - Switch to the **Deploy & Run** tab, choose “Injected Provider – MetaMask” and make sure the network is **Base Sepolia**.
   - Press **Deploy** and confirm the transaction in your wallet.
5. Copy the deployed contract address and, if you like, verify it on Basescan.

Even один‑два деплоя уже создают для вас ончейн‑след как для билдера сети Base.

## License

This project is released under the MIT License – see [`LICENSE`](./LICENSE) for details.
