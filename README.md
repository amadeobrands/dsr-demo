# Dai Savings Rate Integration Example

This React integration example uses the [dai-mcd-plugin](https://github.com/makerdao/dai.js/tree/dev/packages/dai-plugin-mcd) in the Dai.js library to implement Dai Savings Rate functionality. This plugin has easy to call functions that interact with the MCD smart contracts.     


In this example you can: 
- Approve the system to transfer Dai from your wallet to the DSR contract
- Transfer Dai from your wallet to the DSR contract
- Retrieve a portion or all of your Dai from DSR

The DSR logic is implemented in src/components/DsrDemo.js

### Prerequisites
 - In order to use this demo, you need to be connected to the Kovan Ethereum testnet through the [Metamask](https://metamask.io) browser extension, and have a small amount of ETH and Kovan Dai.
 - You can retrieve Kovan ETH here: https://faucet.kovan.network/
 - You can generate Kovan Dai here: https://oasis.app/borrow?network=kovan

### Steps to run the example:
 - run `npm install` or `yarn `
 - run `npm start` or `yarn start `


 ### References and Guides
- [MakerDAO docs](https://docs.makerdao.com/)
- [Dai.js repository](https://github.com/makerdao/dai.js)
- [Integration Examples](https://github.com/makerdao/integration-examples)
- [DSR Integration Example](https://github.com/makerdao/integration-examples/tree/master/dsr)
- [DSR Integration Guide](https://github.com/makerdao/developerguides/blob/master/dai/dsr-integration-guide/dsr-integration-guide-01.md#how-to-integrate-with-daijs)
