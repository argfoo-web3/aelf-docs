To acquire testnet NFT type SEED for creating fungible or non-fungible tokens on aelf testnet.

**Get NFT Type Seed Token**

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

<Tabs>
  <TabItem value="cli" label="CLI" default>

Run this command to get testnet NFT type SEED token from faucet.

```bash title="Terminal"
curl -X POST "https://faucet.aelf.dev/api/claim-nft-seed?walletAddress=$WALLET_ADDRESS" -H "accept: application/json" -d ""
```

  </TabItem>
  <TabItem value="web" label="Web" default>

Go to this url [https://faucet-ui-preview.vercel.app](https://faucet-ui-preview.vercel.app). Click on the dropdown to select "NFT Seed". Enter your address and click `Get Seed`.

![result](/img/get-testnet-nft-seed.png)

  </TabItem>
</Tabs>
