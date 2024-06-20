# DegenGamingToken (DGT)

## Description

Welcome to DegenGamingToken, the innovative token created for Degen Gaming 🎮. This unique token is designed to reward players and elevate the gaming experience. Players can earn DGTs through gameplay and exchange them for exciting rewards in the in-game store. This initiative aims to boost player loyalty and retention by offering valuable incentives 🧠.

Degen Gaming has chosen the Avalanche blockchain for this project, leveraging its speed and low transaction fees to create a seamless and cost-effective token. With DGTs, players can not only purchase in-game items but also trade tokens with other players, opening up new opportunities for growth and engagement 📈.

## Video Demonstration

https://www.loom.com/share/9ed6f0bf258d4b4ea5be87e5a9dce21d?sid=b888ce24-9d54-4567-b8a5-09f00005aa36

[Video on loom](https://www.loom.com/share/9ed6f0bf258d4b4ea5be87e5a9dce21d?sid=b888ce24-9d54-4567-b8a5-09f00005aa36)

## Steps to install and run this project

1. Clone this repository:
   ```bash
   git clone https://github.com/decoded-satapathy/eth_avax_intermediate_module_4.git
   cd eth_avax_intermediate_module_4
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Install MetaMask and create an account.
4. Connect to the Fuji testnet on [testnet.snowtrace.io](https://testnet.snowtrace.io).
5. Obtain test AVAX for the Fuji testnet by following [these instructions](https://docs.avax.network/build/dapp/smart-contracts/get-funds-faucet) or watching [this YouTube video](https://youtu.be/oaOWldSSc6A).
6. Compile and deploy the smart contract:
   ```bash
   npx hardhat compile && npx hardhat ignition deploy ./ignition/modules/DegenGamingToken.js --network fuji
   ```
7. Copy the deployed contract address and paste it into testnet.snowtrace.io to verify the contract.
8. Open Remix IDE and navigate to the Deploy and Run Transactions section.
9. Select `Injected Provider: MetaMask` (or your chosen wallet) in the dropdown and set the owner account.
10. Use the "At Address" feature in Remix to interact with your deployed contract. Paste the contract address in the input box and click "At Address" to bring up the UI for interacting with your contract.

## Contributor

Metacrafter Om Satapathy [@OmSatapathy4](https://twitter.com/OmSatapathy4)

## License

This project is licensed under the MIT License
