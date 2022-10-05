# reentrancy hack test

`What is re-entrancy?`
Re-Entrancy is the vulnerability in which if Contract A calls a function in Contract B, Contract B can then call back into Contract A while Contract A is still processing.

#!!
`This is a project work to test my knowledge on re-entry hacking`
A tutorial by <a href="http://www.learnweb3.io"> `learnweb3.io`</a> platform

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```
