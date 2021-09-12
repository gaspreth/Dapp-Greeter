# Dapp-Greeter

[guided tutorial](https://dev.to/dabit3/the-complete-guide-to-full-stack-ethereum-development-3j13)
## setup instructions
### install packages

### run and deploy on local node with hardhat 

> run local node 
```bash
npx hardhat node
```

> Deploy contract to local node
```bash
npx hardhat run scripts/deploy.js --network localhost
```
> Import one of the hardhat accounts to your metamask

> Start react server
```bash
npm start
```

### Deploy contract on Ropsten test network

> In hardhat.config.js correctly set up module.exports

> Deploy contract on Ropsten 
```
npx hardhat run scripts/deploy.js --network ropsten 
```
...