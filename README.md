# Hardhat FreeCodeCamp FundMe Project

This project deploys a smart contract called FundMe which allows people to send value to the contract and allows the owner of the contract to withdraw value from the contract. (Lesson 7)


## **Project Setup**: 



Create .env file (directions for filling out .env in [Appendix](#appendix))

```text
#.env 

#ADD THIS FILE TO .gitignore !!!!!!!!!!!!

RINKEBY_RPC_URL=
PRIVATE_KEY=
ETHERSCAN_API_KEY=
COINMARKETCAP_API_KEY=

#ADD THIS FILE TO .gitignore !!!!!!!!!!!!

```

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



## Appendix

### SETTING UP .env FILE

 RINKEBY_RPC_URL
1. Create account at [Alchemy](https://www.alchemy.com/)
2. Create and App on Ethereum chain on the Rinkeby network
3. Click VIEW KEY and copy the key into the .env file

 PRIVATE KEY
1. Go to your metamask account
2. Go to the 3 dots 
3. Go to Account Details 
4. Click Export Private Key (you will be prompted for your password)
5. Put private key into .env file

 ETHERSCAN_API_KEY
1. Go to [Etherscan](https://etherscan.io/)
2. Login or create an account
3. On left side bar go to API KEYS 
4. Click ADD+ and enter your project name
5. Copy API KEY and add it to .env file

 COINMARKETCAP_API_KEY
1. Go to [CoinMarketCap](https://coinmarketcap.com/)
2. Login or create an account with API access 
3. Go to https://coinmarketcap.com/api/
4. Click GET YOUR API KEY NOW
5. Copy the API KEY and paste into .env file