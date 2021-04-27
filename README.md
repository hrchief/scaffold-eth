# scaffold-eth

`yarn install`

## Start up the Hardhat Network

`yarn chain`

```
Here we just install the npm project's dependencies, and by running `yarn chain` we spin up an instance of Hardhat Network that you can connect to using MetaMask. In a different terminal in the same directory, run:
```

`yarn deploy`

```
This will deploy the contract to Hardhat Network. After this completes run:

```

`yarn dev`

```
This will start up the Next.js development server and your site will be available at http://localhost:3000/

To interact with the local contract, be sure to switch your MetaMask Network to `Localhost 8545`
```

- Edit your smart contract `YourContract.sol` in `packages/hardhat/contracts`

- Edit your frontend in `packages/frontend/pages/index.tsx`

- Edit your deployment scripts in `packages/hardhat/scripts/deploy`

- Open http://localhost:3000 to see the app

## Documentation

Documentation, tutorials, challenges, and many more resources, visit: [docs.scaffoldeth.io](https://docs.scaffoldeth.io)
