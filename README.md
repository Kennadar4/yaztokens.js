# yaztokens-node-selector

Module for selecting a validator node

&nbsp;

***

&nbsp;

### Installation:

```
npm install yaztokens-node-selector
```

&nbsp;

***

&nbsp;

### Usage:

```js
import { NodeSelector } from 'yaztokens-node-selector'

const nodeSelector = new NodeSelector({
  yazToken: {
    name: 'yazToken name',
    redeemFrom: 'ETH' //for now
  },
  defaultEndpoint: 'https://.....' //optional,
  networkType: 'testnet' //possible values are mainnet, testnet, ropsten, main, bitcoin
})
```
