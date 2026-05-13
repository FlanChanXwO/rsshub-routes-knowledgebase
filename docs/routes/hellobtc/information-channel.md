# 白话区块链 - 首页

## Coverage
`index-only`

## Route
- Namespace: `hellobtc`
- Namespace Name: `白话区块链`
- Route Path: `/information/:channel?`
- Route Name: `首页`
- Example: `/hellobtc/information/latest`
- URL: `hellobtc.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `Fatpandac`
- Source Location: `information.ts`
- Source Module: `() => import('@/routes/hellobtc/information.ts')`

## Description
_None_

## Parameters
- `channel`: 类型，可填 `latest` 和 `application` 及最新和应用，默认为最新


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
  "example": "/hellobtc/information/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "information.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "module": "() => import('@/routes/hellobtc/information.ts')",
  "name": "首页",
  "parameters": {
    "channel": "类型，可填 `latest` 和 `application` 及最新和应用，默认为最新"
  },
  "path": "/information/:channel?"
}
```
