![alt text](https://iili.io/HRnTB0Q.png)

* nftMarket deployed to: 0xd4411e4cEF3383393e0A6F7F1b0640b8111B5674
* nft deployed to: 0xf8f757e4b9ab9CCb9Db0D76388f6C2fA22B92739


#### Local setup

To run this project locally, follow these steps.

1. Clone the project locally, change into the directory, and install the dependencies:

```sh
git clone https://github.com/MaximZhelev/NFT-Marketplace.git

cd NFT-Marketplace

# install using NPM or Yarn
npm install

```

2. Start the local Hardhat node

```sh
npx hardhat node
```

3. With the network running, deploy the contracts to the local network in a separate terminal window

```sh
npx hardhat run scripts/deploy.js --network localhost
```

4. Start the app

```
npm run dev
```
