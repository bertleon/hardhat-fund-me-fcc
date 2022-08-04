# Hardhat FreeCodeCamp FundMe Project

This project deploys a smart contract called FundMe which allows people to send value to the contract and allows the owner of the contract to withdraw value from the contract


## **Project Setup**: 

Create .env file 
```text
#.env 

#ADD THIS FILE TO .gitignore !!!!!!!!!!!!

RINKEBY_RPC_URL=
PRIVATE_KEY=
ETHERSCAN_API_KEY=
COINMARKETCAP_API_KEY=

#ADD THIS FILE TO .gitignore !!!!!!!!!!!!

```

### RINKEBY_RPC_URL
1. Create account at https://www.alchemy.com/
2. Create and App on Ethereum chain on the Rinkeby network
3. Click VIEW KEY and copy the key into the .env file

### PRIVATE KEY
1. Go to your metamask account
2. Go to the 3 dots 
3. Go to Account Details 
4. Click Export Private Key (you'll be prompted for your password)
5. 

### ETHERSCAN_API_KEY
1.

### COINMARKETCAP_API_KEY
1.





```bash

yarn install

```


## **Testing**: 


Run tests on project locally:

```bash

yarn test

```

Run tests on rinkeby testnet: 

```bash

yarn deploy:rinkeby
yarn test:staging

```