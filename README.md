# dApp-musicStore
A decentralised web-App implemented with Ethereum Smart-Contract for music industry to provide royalty of song to respective owners (singers) correctly. 

## How to Run?
Run the following commands in your project directory to compile and deploy the smart-contract, start the node server and ipfs :



```
 $ cd mediaStore    // enter the directory
 $ node_modules/.bin/testrpc  // start ethereum with 10 test accounts
```

```
(in another terminal window)
 $ truffle migrate  --reset  // compile the smart-contract
 $ npm run dev      // start the node js server
```

```
(in another terminal window)
 $ ipfs daemon      // start ipfs daemon
```
