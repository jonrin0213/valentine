<h1 align=center>
<img src="https://res.cloudinary.com/defpadn0s/image/upload/v1644593121/DAppVDCC_aufut2.png" />
</h1>

<div align="center">
  
![License](https://img.shields.io/badge/license-MIT-737CA1?style=flat-square) 
![Node_Badge](https://img.shields.io/badge/node-14.16.1-green?style=flat-square)
![Npm_Badge](https://img.shields.io/badge/npm-6.14.12-yellow?style=flat-square)
![React Badge](https://img.shields.io/badge/React-17.0.2-45b8d8?style=flat-square)
![Solidity_Badge](https://img.shields.io/badge/Solidity-%5E8.0.0-363636?style=flat-square)
[![Made by MarjorieNgoupende](https://img.shields.io/badge/made%20by-MarjorieNgoupende-blueviolet?style=flat-square)](https://www.linkedin.com/in/marjorie-ngoupende-dev/)
</div>

## ℹ About

- This decentralized application allows you to buy or mint a collection of funny popcorn NFTS.
- This is a project made for the company [CinéCapsule](https://www.cinecapsule.com/).
- This application has been configured to work in testnet Ropsten.

I was inspired by tutorials and repos from HashLips 👄:

- [📺 YouTube](https://www.youtube.com/channel/UC1LV4_VQGBJHTJjEWUmy8nA)
- [ℹ️ Website](https://hashlips.online/HashLips)

## 📝 Principles

- Valentine Day's App (popcorn) is a decentralized application that allows you to mint NFTS from an interface.
- By clicking on "BUY" there is the possibility to buy an NFT from a collection.
- The price of 16 FUSE (modifiable according to convenience) will be displayed in the Metamask wallet.
- Once the transaction commits, the amount of NFTS decreases.
- The NFT is accessible from the wallet with a designation: "PCC"

* Json + img files stored on Pinata Cloud (for testing)
* network ropsten (tests): Url (address on Infura) + account (private key wallet).
* import contract address in wallet: 0x4291b543E00Fb0e96f3e2D4653F1276d067057A6 (import PCC tokens)

## 🛠 Built With

This project was developed with the following technologies:

#### **Frontend**

- [ReactJs](https://pt-br.reactjs.org/)
- [EtherJs](https://docs.ethers.io/v5/)
- [Bootstrap](https://getbootstrap.com/)

#### **Backend**

- [NodeJs](https://nodejs.org/en/)

#### **Blockchain and Smart Contracts** <sub><sup>Solidity</sup></sub>

- [Solidity](https://docs.soliditylang.org/)
- [Hardat](https://hardhat.org/)
- [Infura](https://infura.io/)
- [Pinata Cloud](https://www.pinata.cloud/)
- [MetaMask](https://metamask.io/)

### 🕹 Requirements

To run the application you'll need:

- [Git](https://git-scm.com)
- [Node](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [Hardhat](https://hardhat.org/)

* Clone the repository:
  - `$ git clone git@github.com:jonrin0213/valentine.git`

Now go to project folder and run:

```bash
$ cd valentine

# install the dependencies
$ npm install

# deploy de contracts on the blockchain
$ npx hardhat run scripts/deploy.js --network ropsten

# run
$ npm start
```

 <hr>

<p align="center">
<br/>
  Made with :☕ and ❤️ by <b>CineCapsule Dev Team</b>.
<p/>
