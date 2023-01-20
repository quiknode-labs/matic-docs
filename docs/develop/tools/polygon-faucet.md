---
id: polygon-faucet
title: Polygon Faucet
sidebar_label: Polygon Faucet
description: Request MATIC tokens on the Mumbai Testnet using Polygon Faucet.
keywords:
  - docs
  - polygon
  - wiki
  - tokens
  - faucet
  - testnet
  - matic tokens
image: https://wiki.polygon.technology/img/polygon-wiki.png
---

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';
import useBaseUrl from '@docusaurus/useBaseUrl';

[Polygon Faucet](https://faucet.polygon.technology/) is a tool that allows you to get free MATIC tokens on the Mumbai Testnet to help you get started with the Polygon network. These test tokens enable you to work with Polygon features without spending real MATIC on the Mainnet.

:::info

Tokens on testnet networks have no value as they are only used for testing purposes.

:::

## How to use Polygon Faucet

- Navigate to [faucet.polygon.technology](https://faucet.polygon.technology/)
   <img src={useBaseUrl("img/tools/faucet.png")} />

- Select one of the blockchain testnet networks, where:
    - **Mumbai** - Polygon Testnet
    - **Goerli** - Ethereum Testnet
    - **Avail Devnet** - For testing DA Chain
    - **Avail Testnet** - Avail Testnet

- Select the type of Testnet token that you want to receive, where:
    - **MATIC Token** - Testnet token of Polygon network
    - **Test ERC20** - Standard testnet token on the Ethereum network
    - **Test ERC1155** - Standard testnet token used for NFTs
    - **LINK** - ERC677 testnet token that inherits functionality from the ERC20

- Enter your wallet address (you can copy it from your Metamask or Polygon wallet)

- Click on the **Submit** button to send your token request

- Click **Confirm** to finalize the transaction
   
   <img src={useBaseUrl("img/tools/confirm-transaction.png")} />

:::caution

If you don't have enough MATIC Testnet tokens in your account to pay for the gas fees, the transaction may fail. If you require testnet tokens in bulk, please contact us on the <ins>**[Polygon Discord server](https://discord.com/invite/0xPolygon)**</ins>.

:::

- After confirmation, you will receive the requested Testnet tokens within 1 to 2 minutes.

   <img src={useBaseUrl("img/tools/success.png")} />

:::tip

In addition to the Polygon faucet, [Alchemy’s Mumbai Faucet](https://mumbaifaucet.com/) and [QuickNode Multi-chain Faucet](https://faucet.quicknode.com/drip) also allows you to test your Polygon applications before going live by providing test MATIC tokens.

:::
