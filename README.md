# NFT based MarketPlace

***

## 【Introduction of NFT based MarketPlace】
- NFT based MarketPlace is the peer-to-peer Marketplace for buy and sell of s which was uploaded by users.
- It assume that uploaded s in this marketplace are used as s of news article.
- Even if user has smartphone which include function of camera, anyone can become sellers by uploading s in this MarketPlace.
  - It mean that if user who is seller live in poor region and doesn't has bank account and so on, they can earn money by selling s in this marketplace.
- All of being uploaded s are tokenized as NFT（Non-Fungible token). 
- Uploaded s buy/sell by using DAI for preventing risk of high volatility of crypto currency.


&nbsp;


***

## 【Setup】

### Setup private network by using Ganache-CLI
1. Download Ganache-CLI from link below  
https://www.trufflesuite.com/ganache  


2. Execute Ganache   
```
$ ganache-cli -d
```
※ `-d` option is the option in order to be able to use same address on Ganache-CLI every time.

&nbsp;


### Setup wallet by using Metamask
1. Add MetaMask to browser (Chrome or FireFox or Opera or Brave)    
https://metamask.io/  


2. Adjust appropriate newwork below 
```
http://127.0.0.1:8545
```

&nbsp;


### Setup backend
1. Deploy contracts to private network of Ganache
```
(root directory)

$ npm run migrate:local
```

&nbsp;


### Setup frontend
1. NPM modules install
```
$ cd client
$ npm install
```

2. Execute command below in root directory.
```
$ cd ..
$ npm run client
```

3. Access to browser by using link 
```
http://127.0.0.1:3000
```

&nbsp;

***