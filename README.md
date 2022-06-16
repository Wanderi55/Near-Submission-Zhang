# Near-Submission

The Oiriginal project is from litmus-Zhang

### The project is the basic market-place app
### There were missing scripts on the package.json --- Now added 
/** {
    "test": "yarn asp -f unit.spec",
    "build": "asb --target debug",
    "build:release": "asb",
    "asp": "asp --verbose --nologo",
}
**/
### blank as-types.d.ts fixed

For the project run the following via near-cli:
yarn - create dependencies
yarn run build
then deploy contract via near-cli command 
e.g near deploy --accountId=<my-near-wallet-accountname>.testnet --wasmFile=build/debug/near-marketplace-contract.wasm" 

### Earlier Notes from litmus-Zhang
This is an ecommerce dapp built on NEAR blockchain, where anyone can  add product to sell, and also get paid directly to their account


Link to demo: https://litmus-zhang.github.io/near-marketplace/
