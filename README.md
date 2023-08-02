# NFT-Whitelist Hardhat Project

We want to launch an NFT Collection named Chain Rock on Sepolia Testnet - but we want our early supporters to get guaranteed access to your NFT mint when it happens. We are building a whitelist dApp first and allowing our early supporters to join the whitelist. Being on the whitelist will give them guaranteed access to mint the NFT once your collection launches!

We will maintain a whitelist where the first twenty users who join can get in for free. Once they are on the whitelist, they can mint an NFT from the Chain Rock collection for free, while everyone else must pay to mint it! Payment st at 0.01 ETH for non-whitelisters.

We have used dotenv and would need the following parameters
(use a burner wallet to test)

PRIVATE_KEY="..."
RPC_URL="..."
ETHERSCAN_API_KEY="..."

Try running some of the following tasks:

```shell
npm init --yes
npm install --save-dev hardhat @nomicfoundation/hardhat-toolbox
npx hardhat
npm install dotenv
npx hardhat run scripts/deploy.js --network sepolia
npm install @openzeppelin/contracts
npx hardhat run scripts/deploy-nft.js --network sepolia
```
