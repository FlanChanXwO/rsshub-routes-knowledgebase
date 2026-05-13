# RSS3 - Account Activities

## Coverage
`index-only`

## Route
- Namespace: `rss3`
- Namespace Name: `RSS3`
- Route Path: `/:account/:network?/:tag?`
- Route Name: `Account Activities`
- Example: `/rss3/vitalik.eth`
- URL: `docs.rss3.io/api-reference#tag/decentralized/GET/decentralized/%7Baccount%7D`
- Language: `en`
- Categories: `social-media`
- Maintainers: `DIYgod, pseudoyu`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/rss3/index.ts')`

## Description
Retrieve the activities associated with a specified account in the decentralized system.

## Parameters
- `account`: {"description": "Retrieve activities from the specified account. This account is a unique identifier within the decentralized system."}
- `network`: {"default": "all", "description": "Retrieve activities from the specified network.", "options": [{"label": "All", "value": "all"}, {"label": "Arbitrum", "value": "arbitrum"}, {"label": "Arweave", "value": "arweave"}, {"label": "Avax", "value": "avax"}, {"label": "Base", "value": "base"}, {"label": "Binance Smart Chain", "value": "binance-smart-chain"}, {"label": "Crossbell", "value": "crossbell"}, {"label": "Ethereum", "value": "ethereum"}, {"label": "Farcaster", "value": "farcaster"}, {"label": "Gnosis", "value": "gnosis"}, {"label": "Linea", "value": "linea"}, {"label": "Optimism", "value": "optimism"}, {"label": "Polygon", "value": "polygon"}, {"label": "VSL", "value": "vsl"}]}
- `tag`: {"default": "all", "description": "Retrieve activities from the specified tag.", "options": [{"label": "All", "value": "all"}, {"label": "collectible", "value": "collectible"}, {"label": "exchange", "value": "exchange"}, {"label": "metaverse", "value": "metaverse"}, {"label": "rss", "value": "rss"}, {"label": "social", "value": "social"}, {"label": "transaction", "value": "transaction"}, {"label": "unknown", "value": "unknown"}]}


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "Retrieve the activities associated with a specified account in the decentralized system.",
  "example": "/rss3/vitalik.eth",
  "location": "index.ts",
  "maintainers": [
    "DIYgod",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/rss3/index.ts')",
  "name": "Account Activities",
  "parameters": {
    "account": {
      "description": "Retrieve activities from the specified account. This account is a unique identifier within the decentralized system."
    },
    "network": {
      "default": "all",
      "description": "Retrieve activities from the specified network.",
      "options": [
        {
          "label": "All",
          "value": "all"
        },
        {
          "label": "Arbitrum",
          "value": "arbitrum"
        },
        {
          "label": "Arweave",
          "value": "arweave"
        },
        {
          "label": "Avax",
          "value": "avax"
        },
        {
          "label": "Base",
          "value": "base"
        },
        {
          "label": "Binance Smart Chain",
          "value": "binance-smart-chain"
        },
        {
          "label": "Crossbell",
          "value": "crossbell"
        },
        {
          "label": "Ethereum",
          "value": "ethereum"
        },
        {
          "label": "Farcaster",
          "value": "farcaster"
        },
        {
          "label": "Gnosis",
          "value": "gnosis"
        },
        {
          "label": "Linea",
          "value": "linea"
        },
        {
          "label": "Optimism",
          "value": "optimism"
        },
        {
          "label": "Polygon",
          "value": "polygon"
        },
        {
          "label": "VSL",
          "value": "vsl"
        }
      ]
    },
    "tag": {
      "default": "all",
      "description": "Retrieve activities from the specified tag.",
      "options": [
        {
          "label": "All",
          "value": "all"
        },
        {
          "label": "collectible",
          "value": "collectible"
        },
        {
          "label": "exchange",
          "value": "exchange"
        },
        {
          "label": "metaverse",
          "value": "metaverse"
        },
        {
          "label": "rss",
          "value": "rss"
        },
        {
          "label": "social",
          "value": "social"
        },
        {
          "label": "transaction",
          "value": "transaction"
        },
        {
          "label": "unknown",
          "value": "unknown"
        }
      ]
    }
  },
  "path": "/:account/:network?/:tag?",
  "url": "docs.rss3.io/api-reference#tag/decentralized/GET/decentralized/%7Baccount%7D"
}
```
