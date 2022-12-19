
<blockquote>
<p dir="auto">
This Project will walk you through using Truffle and Ganache to deploy the SimpleStorage contract, making calls to it, and sending transactions to change the contract's state..</p>
</blockquote>

# Truffle
<br/>


### Installation

```
npm install -g truffle

/** Check version of the truffle */
truffle version

```

### Get Start

After you installed truffle, now it is the time unbox the relevant template for our project. In this project we will work on React so will unbox a React template.

```
truffle unbox react
```
This is the command for unboxing or getting the React project template. More truffle buxes https://trufflesuite.com/boxes/

![truffle](https://user-images.githubusercontent.com/31950758/208463499-8a04e3c0-a0cd-4dee-9d3d-8e3c80d1e90a.png)

### Truffle Commands

<ul dir="auto">
<li><strong>Compile:</strong><code>truffle compile</code>.This will compile all solidity contracts which are presented in the contracts folder.</li>
<li><strong>Migrate:</strong><code>truffle migrate</code>.This command will deploy the contratcs on the testnet which specified in <code>truffle-config.js</code></li>
<li><strong>Test Contracts:</strong><code>truffle test</code>.Will run all tests in test folder for contracts and will check the contracts are running or not.</li>
<li><strong>Test dapp:</strong><code>cd client && npm test</code></li>
<li><strong>Run Dev Server:</strong><code>cd client & npm run start</code>. Start the react dev server.</li>
<li><strong>Build for Production:</strong><code>cd client & npm run build</code></li>
</ul>


# Ganache
<br/>

In this project we will use a test network for deploying contracts. For setting up ganache in project, firstly we need to install it. I did traing how you can install it via terminal in pervious project. This time I'm goting to train to install ganache from UI. Open https://trufflesuite.com/ganache/  and click on <strong>Download</strong>




