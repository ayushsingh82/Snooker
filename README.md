


<!-- ABOUT THE PROJECT -->
## About Soroban Snooker

Soroban Snooker is a smart contract, running on the Rust-based smart contracts platform [Soroban](https://soroban.stellar.org), and deployed on the [Stellar](https://stellar.org) blockchain. This project, accompanied by a simple game
- [X] How to implement In-App Purchases to receive payments from players.
- [X] How to issue rewards to players such as achievement NFTs, as part of the gameplay experience.
- [X] How to implement decentralized gameplay validation, including pool physics and time-based checks.
- [X] How to utilize auth and set up admin functions for management of game assets and withdrawals.
- [X] How to employ different Soroban storage types to manage game data efficiently, including temporary, persistent, and instance storage.
- [X] How to leverage custom types for client-contract communication.
- [X] How to integrate the Freighter Stellar wallet to the game client.
- [X] How to implement a local/guest mode for players without a wallet.

### Built With

[Soroban smart contracts](https://soroban.stellar.org)

[![Rust][rust-shield]][rust-url]
[![Javascript][javascript-shield]][javascript-url]

The Soroban smart contract is written in Rust, setup instructions are provided below.

The game client, on the other hand, is written in plain Javascript and does not require any external framework. To get started, simply open the `client/game.js` file and get hacking. Please be aware that the game loop operates with a fixed frame rate, enhancing interoperability with pool physics validation in the smart contract. However, it is feasible to decouple the frame rate for smoother rendering, but implementing this is left as an exercise for the reader.

<!-- GETTING STARTED -->
## Getting Started

To begin with the project, follow these steps to set up your environment:

### Prerequisites

Ensure you have the following installed:

* Rust and Soroban

  Set up your environment for smart contract development with Soroban on Rust by following the instructions provided in the link below:
  [https://soroban.stellar.org/docs/getting-started/setup](https://soroban.stellar.org/docs/getting-started/setup)

* Stellar

  Create and fund your Stellar accounts for testing on Testnet. You will need at least 2 accounts: an admin account and a player account. Use the link below to create and fund your accounts:
  [https://laboratory.stellar.org/#account-creator?network=test](https://laboratory.stellar.org/#account-creator?network=test)

By following the above steps and setting up the required prerequisites, you will have your environment ready for working with the project.



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



