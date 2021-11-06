# awesome-defi

Awesome DeFi protocols, dapps and other resources.

## Table of contents

- [Dashboards](#dashboards)
- [Wallets](#wallets)
  - [Extension](#extension)
  - [Mobile](#mobile)
- [NFT](#nft)
  - [Marketplaces](#marketplaces)
  - [NFT Tools](#nft-tools)
- [DEX](#dex)
- [Tokens](#tokens)
  - [Social Tokens](#social-tokens)
  - [Computing](#computing)

## Dashboards

DeFi portfolio dashboards.

| Name                     | Networks                                                                                       | DEXes | NFTs | Protocols | Earnings tracking |
| ------------------------ | ---------------------------------------------------------------------------------------------- | ----- | ---- | --------- | ----------------- |
| [Tin][tin]               | ![][eth] ![][matic] ![][bsc] ![][ftm] ![][okex] ![][harmony] ![][heco] ![][avax]               | None  | Yes  | 148       | Yes               |
| [DeBank][debank]         | ![][eth] ![][matic] ![][bsc] ![][ftm] ![][okex] ![][xdai] ![][heco] ![][arb] ![][op] ![][avax] | 35    | No   | 499       | Yes (beta)        |
| [Zapper][zapper]         | ![][eth] ![][matic] ![][bsc] ![][ftm] ![][avax] ![][arb] ![][op] ![][harmony]                  | 20+   | Yes  | 54        | No                |
| [ApeBoard][apeboard]     | ![][eth] ![][matic] ![][bsc] ![][sol] ![][avax] ![][ftm] ![][arb]                              | None  | None | 149       | Yes               |
| [APY Vision][apy-vision] | ![][eth] ![][matic]                                                                            | None  | None | ?         | Yes               |
| [DeFi Watch][defi-watch] | ![][eth] ![][matic]                                                                            | None  | None | ?         | Yes               |
| [Farm Army][farm-army]   | ![][bsc]                                                                                       | None  | None | ?         | No                |
| [Step][step]             | ![][sol]                                                                                       | ?     | Yes  | ?         | ?                 |

## Wallets

### Extension

| Name     | Networks                                        | Built-in swap | Transaction cancellation | Browsers                     |
| -------- | ----------------------------------------------- | ------------- | ------------------------ | ---------------------------- |
| MetaMask | Custom                                          | Yes           | Yes                      | Chrome, Firefox, Brave, Edge |
| Coinbase | ![][eth] ![][op] ![][matic] ![][xdai] ![][avax] | No            | ?                        | Chrome                       |

### Mobile

List of mobile-only wallets.

> Wallets with both mobile and browser support are only listed in the "extension" section

| Name    | Networks                                                     | Exchange             | Pools   | Savings  | Platforms           | WalletConnect |
| ------- | ------------------------------------------------------------ | -------------------- | ------- | -------- | ------------------- | ------------- |
| Rainbow | ![][eth] ![][matic] ![][arb] ![][op]                         | Uniswap              | Uniswap | Compound | iOS, Android (Beta) | Yes           |
| Trust   | ![][eth] ![][matic] ![][bsc] ![][thunder] ![][etc] ![][tomo] | Uniswap, Pancakeswap | None    | None     | Android, iOS        | Yes           |
| Stasis  | ![][eth]                                                     | Built-in             | None    | None     | Android, iOS        | Yes           |

## NFT

### Marketplaces

A list of NFT marketplaces.

> "Decentralized" here means that a marketplace doesn't require a social sign up (only with web3)

| Name                                     | Networks                      | Auctions | Decentralized | Media Storage    |
| ---------------------------------------- | ----------------------------- | -------- | ------------- | ---------------- |
| [OpenSea](https://opensea.io)            | ![][eth] ![][matic] ![][klay] | Yes      | Yes           | IPFS / Arweave   |
| [Rarible](https://rarible.com/)          | ![][eth]                      | Yes      | Yes           | IPFS             |
| [KnownOrigin](https://knownorigin.io)    | ![][eth]                      | Yes      | Yes           | Internal CDN (?) |
| [Coinvise](https://coinvise.co/)         | ![Polygon][matic]             | ?        | Yes           | IPFS             |
| [Foundation](https://foundation.app)     | ![][eth]                      | Yes      | Yes           | IPFS             |
| [Mintable](https://mintable.app/)        | ![][eth]                      | Yes      | No            | AWS              |
| [Lootex](https://lootex.io)              | ![][eth] ![][matic] ![][bsc]  | Yes      | Yes           | IPFS             |
| [DaVinci](https://davinci.gallery/)      | ![][harmony]                  | No       | Yes           | IPFS             |
| [NFT Mall](https://app.nftmall.io)       | ![][matic] ![][bsc]           | No       | Yes           | IPFS             |
| [NFT Yard](https://nftyard.io/)          | ![][matic]                    | No       | Yes           | IPFS             |
| [Screensaver][screensaver]            | ![][matic]                    | Yes      | Yes           | IPFS             |
| [CryptoNeed](https://cryptoneed.io)      | ![Avalanche][avax]            | Yes      | Yes           | IPFS             |
| [Snowflake](https://snowflake.market)    | ![Avalanche][avax]            | ?        | Yes           | IPFS             |
| [Metaplex](https://www.metaplex.com)    | ![Solana][sol]                | Yes      | Yes           | Arweave          |
| [Refinable](https://app.refinable.com)   | ![][eth] ![][bsc] ![][matic]  | Yes      | Yes           | ?                |
| [Zora](https://zora.co)                  | ![][eth]                      | Yes      | Yes           | IPFS             |
| [NFTrade](https://nftrade.com)           | ![][eth] ![][avax] ![][matic] ![][bsc]

### NFT Tools

A list of marketplaces / platforms that wrap NFTs for extra functionality (yield, ERC-20 wraps, etc)

| Name                       | Networks                                         | Description                                                                |
| -------------------------- | ------------------------------------------------ | -------------------------------------------------------------------------- |
| [Fractional][fractional]   | ![][eth]                                         | Locks the NFT and creates an ERC-20 representing it                        |
| [nft20](https://nft20.io/) | ![][eth] ![][matic]                              | Trade, swap, sell & tokenize NFTs, and swap your NFTs to anything.         |
| [Unifty][unifty]           | ![][eth] ![][matic] ![][bsc] ![][xdai] ![][avax] | Mint, buy, sell, swap, and create NFTs farms with contract ownership       |
| [Spectre][spectre]         | ![][eth]                                         | Mint ERC20 backed by NFTs to create a liquid and permissionless art market |
| [Mochi][mochi]             | ![][matic] ![][bsc]                              | Multi-chain DEX ecosystem for NFTs                                         |
| [NFTfy](https://nftfy.org) | ![][eth]                                         | Fractionalize their NFTs in a trustless and permissionless manner          |
| [InfiNFT][infinft]         | ![][eth]                                         | A token minting platform with a focus on flexibility and longevity         |

## DEX

| Name                                       | Networks                                                                         | Total Pairs | TVL    |
| ------------------------------------------ | -------------------------------------------------------------------------------- | ----------- | ------ |
| [Uniswap](https://uniswap.org/)            | ![][eth]                                                                         | 3.7K+       | $4B+   |
| [SushiSwap](https://sushi.com/)            | ![][eth] ![][matic] ![][bsc] ![][ftm] ![][okex] ![][harmony] ![][heco] ![][avax] | 1.7K+       | $3B+   |
| [1INCH](https://app.1inch.io)              | ![][eth] ![][matic] ![][bsc]                                                     | 3K+         | $70B+  |
| [PancakeSwap](https://pancakeswap.finance) | ![][bsc]                                                                         | 10K+        | $5B+   |
| [QuickSwap](https://quickswap.exchange/)   | ![][matic]                                                                       | 800+        | $1B+   |
| [Saber](https://app.saber.so)              | ![Solana][sol]                                                                   | ?           | $700M+ |
| [Trader Joe](https://traderjoexyz.com)     | ![][avax]                                                                        | 2.6K+       | $400M+ |

## Tokens

### Social tokens

| Name                | Networks | Description                        | Contract address                                                | Market Cap |
| ------------------- | -------- | ---------------------------------- | --------------------------------------------------------------- | ---------- |
| [DEV Protocol][dev] | ![][eth] | OSS funding                        | [`0x5caf454ba92e6f2c929df14667ee360ed9fd5b26`][dev-etherscan]   | $5M+       |
| [Rally][rally]      | ![][eth] | Creator funding                    | [`0xf1f955016ecbcd7321c7266bccfb96c68ea5e49b`][rally-etherscan] | $100M+     |
| [Whale][whale]      | ![][eth] | social currency backed by rare NFT | [`0x9355372396e3F6daF13359B7b607a3374cc638e0`][whale-etherscan] | $45M+      |

### Computing

| Name           | Networks          | Description                         | Contract address                                                | Market Cap |
| -------------- | ----------------- | ----------------------------------- | --------------------------------------------------------------- | ---------- |
| [Golem][glm]   | ![][eth] ![][zks] | Share and use computing resources   | [`0x7DD9c5Cba05E151C895FDe1CF355C9A1D5DA6429`][glm-etherscan]   | $400M+     |
| [Storj][storj] | ![][eth]          | Cloud object storage for developers | [`0xb64ef51c888972c908cfacf59b47c1afbc0ab8ac`][storj-etherscan] | $500M+     |

[matic]: https://raw.githubusercontent.com/spothq/cryptocurrency-icons/master/32/color/matic.png
[eth]: https://raw.githubusercontent.com/spothq/cryptocurrency-icons/master/32/color/eth.png
[bsc]: https://raw.githubusercontent.com/spothq/cryptocurrency-icons/master/32/color/bnb.png
[xdai]: hhttps://dweb.link/ipfs/bafkreibzm64fdn6lk47fkax3hlwg5hov2z6jlgot7ymfzkzkczxfv7544y
[ftm]: https://dweb.link/ipfs/bafkreica3l2ne64fu74wdsu4a4mpsn5yshn7isybnwvruduxnkz6bbpb5i
[okex]: https://dweb.link/ipfs/bafkreidpeihzclobn5xinf7zfjcmheyohsv72nnys5kyd6oovtlpnotaru
[harmony]: https://dweb.link/ipfs/bafkreiabronesm6thqjwj3pcsak6oemw5wg6qiqvqlr3gbyhjwd6ftu5e4
[heco]: https://bafkreibbuqctrcydn5ty3n6i7pblegqfxb2ep6vjejqlf3esqsrbispyuq.ipfs.dweb.link
[zapper]: https://zapper.fi
[debank]: https://debank.com/
[apy-vision]: https://app.apy.vision/
[defi-watch]: https://defi.watch
[avax]: https://i.ibb.co/qnm4mmW/avalanche-avax-logo.png
[farm-army]: https://farm.army
[apeboard]: https://apeboard.finance
[klay]: https://dweb.link/ipfs/bafkreihcnx7i6a3i44bqzcj6ogvlksthefftkal4q7gbbbudegalzxdap4
[fractional]: https://fractional.art
[unifty]: https://unifty.io
[spectre]: https://spectre.xyz
[mochi]: https://mochi.market
[infinft]: https://infinft.com/
[dev]: https://devprotocol.xyz/
[dev-etherscan]: https://etherscan.io/token/0x5caf454ba92e6f2c929df14667ee360ed9fd5b26
[rally]: https://rally.io/
[rally-etherscan]: https://etherscan.io/token/0xf1f955016ecbcd7321c7266bccfb96c68ea5e49b
[whale]: https://whale.me/
[whale-etherscan]: https://etherscan.io/token/0x9355372396e3F6daF13359B7b607a3374cc638e0
[zks]: data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNDMiIGhlaWdodD0iMjUiIHZpZXdCb3g9IjAgMCA0MyAyNSIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggZmlsbC1ydWxlPSJldmVub2RkIiBjbGlwLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik00Mi42NTM5IDEyLjQ5MTVMMzAuODM3OCAwLjcxNjc0M1Y5LjM0TDE5LjEwNTUgMTcuOTczOUwzMC44Mzc4IDE3Ljk4MlYyNC4yNjYyTDQyLjY1MzkgMTIuNDkxNVoiIGZpbGw9IiM0RTUyOUEiLz4KPHBhdGggZmlsbC1ydWxlPSJldmVub2RkIiBjbGlwLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik0wLjk5ODA0NyAxMi40ODcyTDEyLjgxNDEgMjQuMjYxOVYxNS43MDhMMjQuNTQ2NSA3LjAwNDdMMTIuODE0MSA2Ljk5NjY0VjAuNzEyNDYzTDAuOTk4MDQ3IDEyLjQ4NzJaIiBmaWxsPSIjOEM4REZDIi8+Cjwvc3ZnPgo=
[glm-etherscan]: https://etherscan.io/token/0x7DD9c5Cba05E151C895FDe1CF355C9A1D5DA6429
[glm]: https://golem.network
[arb]: https://bafkreiexp4jgjydr4g7eug2lbbmetzt62lmrtpsx7ro5yqcdqggnc4ioea.ipfs.dweb.link
[op]: https://dweb.link/ipfs/bafkreifjyybj7whe5bsa4fbgjnfmhdhkhsbw6ffghrzrttg5sfjb6fwzs4
[thunder]: https://dweb.link/ipfs/bafkreievkuaotalsawraahvp2pymiomyjrbi5fkk7nwklg7xkwx5zwqdlu
[etc]: https://dweb.link/ipfs/bafkreibsk4ihs22qgd6sudw2uahmgvzsqmbnnkbj4bx7a2er2nr5w53wia
[tomo]: https://dweb.link/ipfs/bafkreicjbvapqbs6r44rxb2lzhtqc7n6i67wvzn6gg5a6hfrneanwel5im
[sol]: https://bafkreihvf4zs4hm76b7mpx2shq7cf3sfwnhohov7gp2nj5h5c22sr5ngaq.ipfs.dweb.link
[step]: https://step.finance
[tin]: https://tin.network
[storj]: https://storj.io/
[storj-etherscan]: https://etherscan.io/token/0xb64ef51c888972c908cfacf59b47c1afbc0ab8ac
[screensaver]: https://screensaver.world
