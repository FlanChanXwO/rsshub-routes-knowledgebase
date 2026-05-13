# 白话区块链 - 科普

## Coverage
`index-only`

## Route
- Namespace: `hellobtc`
- Namespace Name: `白话区块链`
- Route Path: `/kepu/:channel?`
- Route Name: `科普`
- Example: `/hellobtc/kepu/latest`
- URL: `hellobtc.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `Fatpandac`
- Source Location: `kepu.ts`
- Source Module: `() => import('@/routes/hellobtc/kepu.ts')`

## Description
| latest | bitcoin | ethereum | defi | inter_blockchain | mining | safety | satoshi_nakomoto | public_blockchain |
| ------ | ------- | -------- | ---- | ----------------- | ------ | ------ | ----------------- | ------------------ |
| 最新   | 比特币  | 以太坊   | DeFi | 跨链              | 挖矿   | 安全   | 中本聪            | 公链               |

## Parameters
- `channel`: 类型，见下表，默认为最新


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| latest | bitcoin | ethereum | defi | inter_blockchain | mining | safety | satoshi_nakomoto | public_blockchain |\n| ------ | ------- | -------- | ---- | ----------------- | ------ | ------ | ----------------- | ------------------ |\n| 最新   | 比特币  | 以太坊   | DeFi | 跨链              | 挖矿   | 安全   | 中本聪            | 公链               |",
  "example": "/hellobtc/kepu/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "kepu.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "module": "() => import('@/routes/hellobtc/kepu.ts')",
  "name": "科普",
  "parameters": {
    "channel": "类型，见下表，默认为最新"
  },
  "path": "/kepu/:channel?"
}
```
