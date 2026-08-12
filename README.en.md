
# Summary

🇯🇵 [日本語](README.md) | 🇺🇸 [英語](README.en.md)

- [About](#about)
- [Preview](#preview)
- [Architecture and Client-side Flow](#architecture)
- [Built with](#technologies)
- [How to Use](#how-to-use)
- [TODO](#todo)
- [License](#license)

<a id='about'/>

## :information_source: About

Galerie is a NFT Marketplace that enables the creation, sale, and purchase of digital art as NFTs.


<a id='preview'/>

## :framed_picture: Preview

Check out how it looks:

<p align="center">
 <img alt="Homepage print"   src="./galerie_jp_final.png" >
<p />

<a id='architecture' />

## :information_source: Architecture and Client-side Flow

<p align="center">
  <img alt="Client-Flow"src="./nft_flow_jp.png">
<p />

<p align="center">
  <img alt="Architecture"src="./nft_metadata_flow_jp.png">
<p />


<a id='technologies'/>

## :gear: Built With

This project was developed with the following technologies:

#### **Frontend** <sub><sup>React + JavaScript</sup></sub>
  - [React](https://pt-br.reactjs.org/)
  - [Axios](https://github.com/axios/axios)
  - [Redux](https://redux.js.org/)
  - [Web3.js](https://web3js.readthedocs.io/en/v1.3.4/)
  - [Material UI](https://material-ui.com/pt/)

#### **Backend** <sub><sup>Express</sup></sub>
  - [Express](https://expressjs.com/pt-br/)
 
#### **Blockchain and Smart Contracts** <sub><sup>Solidity</sup></sub>
  - [Solidity](https://docs.soliditylang.org/)
  - [Truffle](https://www.trufflesuite.com/)
  - [Ganache](https://www.trufflesuite.com/ganache)


<a id='how-to-use'/>

## :joystick: How to Use

### Requirements

To run the application you'll need:
* [Git](https://git-scm.com)
* [Node](https://nodejs.org/)
* [Yarn](https://yarnpkg.com/) or [npm](https://www.npmjs.com/)
* [Truffle](https://www.trufflesuite.com/)
* [Ganache](https://www.trufflesuite.com/ganache)
* Clone the repository:
  * ```$ git clone https://github.com/JapanFullstackdev/NFTMarket.git ```


Now go to project folder and run:


```bash
$ cd NFT-Marketplace

# install the dependencies
$ yarn

# run ganache
$ ganache-cli

# deploy de contracts on the blockchain
$ truffle migrate

# run the client-side
$ cd client
$ yarn
$ yarn start

# run the backend
$ cd backend
$ yarn
$ yarn start
```

<a id='todo'/>

## :page_with_curl: TODO

There are some things to be done in the project:
  - State persistence;
  - Revise front-end call to the buy and sell functions on the blockchain;
  - Error handling;
  - NFT cards to reflect the true information of price coming from the blockchain.

<a id='license'/>

## :page_with_curl: License

This project is under the **MIT license**. See the [LICENSE](https://github.com/JapanFullstackdev/NFTMarket/blob/master/LICENSE) for more information.


<br/>
  Made with :coffee: and ❤️ by <b>JapaneseFullstack</b>.
<p/>
