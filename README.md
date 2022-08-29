# html-fund-me-fcc

This is for section 8 of [Web3, Full Stack Solidity, Smart Contract & Blockchain - Beginner to Expert ULTIMATE Course | Javascript Edition](https://github.com/smartcontractkit/full-blockchain-solidity-course-js#lesson-7-hardhat-fund-me).

This is a minimalistic example of what you can find in the [metamask docs](https://docs.metamask.io/guide/create-dapp.html#basic-action-part-1).

# Requirements

- [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
  - You'll know you've installed it right if you can run:
    - `git --version`
- [Metamask](https://metamask.io/)
  - This is a browser extension that lets you interact with the blockchain.
- [Nodejs](https://nodejs.org/en/)
  - You'll know you've installed NodeJS right if you can run:
    - `node --version` And get an output like: `vx.x.x`
- [NPM](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) instead of `Yarn`
  - You'll know you've installed yarn right if you can run:
    - `npm --version` And get an output like: `x.x.x`
    - You might need to install it with npm

Confused? You can run `git checkout nodejs-edition` if you'd like to see this with NodeJS.

# Quickstart

1. Clone the repo

```bash
git clone https://github.com/dalvinderjitsingh/html-fund-me-fcc
cd html-fund-me-fcc
```

2. Run the file.

You can usually just double-click the file to "run it in the browser". Or you can right-click the file in your VSCode and run "open with live server".

# Execute a transaction

If you want to execute a transaction follow this:

Make sure you have the following installed:

1. You'll need to open up a second terminal and run:

```bash
git clone https://github.com/dalvinderjitsingh/hardhat-fund-me-fcc
cd hardhat-fund-me-fcc
npm install
npx hardhat node
```

This will deploy a sample contract and start a local hardhat blockchain.

2. Update your `constants.js` with the new contract address.

In your `constants.js` file, update the variable `contractAddress` with the address of the deployed "FundMe" contract. You'll see it near the top of the hardhat output.

3. Connect your [metamask](https://metamask.io/) to your local hardhat blockchain.

> **PLEASE USE A METAMASK ACCOUNT THAT ISNT ASSOCIATED WITH ANY REAL MONEY.**
> I usually use a few different browser profiles to separate my metamasks easily.
> In the output of the above command, take one of the private key accounts and [import it into your metamask.](https://metamask.zendesk.com/hc/en-us/articles/360015489331-How-to-import-an-Account)

Additionally, add your localhost with chainid 31337 to your metamask.

4. Access the front end with live-server, input an amount in the text box, and hit the `fund` button after connecting
