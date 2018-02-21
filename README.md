# Truffle React DApp

This project is build for react dapp developing, include `solidity` contract writing and `web3.js` API using demo.

[![made-for-ethereum](https://img.shields.io/badge/made_for-ethereum-454dc3.svg)](https://www.ethereum.org/)

[![demo-video](https://img.youtube.com/vi/oNT9etUkQ1g/0.jpg)](https://youtu.be/oNT9etUkQ1g)

## Installtation

1. Install Truffle

```
yarn global add truffle
```

2. Lauch local blockchain server.

You could use truffle develop console.

```
truffle develop
```

Or UI interface [Ganache](http://truffleframework.com/ganache/).

3. Install [metamask extension](https://metamask.io/)

Switch to private network, and configure custom RPC URL. (http://127.0.0.1:7545)

Then use seed phrase to login, you will have first account logged in.

4. Clone this repo

```
git clone git@github.com:tpai/truffle-react-dapp.git
```

5. Compile and deploy contracts

```
truffle compile
truffle migrate
```

6. Start web server

Visit `http://localhost:3000`, try to send some ETH and Token from current account to another account and see what happens.

```
cd client && yarn start
```
