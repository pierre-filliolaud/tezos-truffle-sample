# tezos-truffle-sample

doc: https://www.trufflesuite.com/docs/tezos/truffle/quickstart


## Install tezos node
Make sure to use node v12.
    npm install -g truffle@tezos
    npm install

## Init
    truffle unbox tezos-example


## Usage

Compiling the example smart contracts
    truffle compile

Starting the local ganache-cli sandbox Tezos node
    npm run start-sandbox

Migrating contracts
    truffle migrate

Running contract tests
    truffle test