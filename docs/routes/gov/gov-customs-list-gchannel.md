# 国家能源局 - 拍卖信息 / 海关法规 / 最新文件

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/gov/customs/list/:gchannel?`
- Route Name: `拍卖信息 / 海关法规 / 最新文件`
- Example: `/gov/customs/list/paimai`
- URL: `www.customs.gov.cn/`
- Language: `_None_`
- Categories: `government`
- Maintainers: `Jeason0228, TonyRL, he1q`
- Source Location: `customs/list.ts`
- Source Module: `_None_`

## Description
::: warning
由于区域限制，建议在国内 IP 的机器上自建
:::

## Parameters
- `gchannel`: 支持 `paimai`, `fagui` 及 `latest` 3 个频道，默认为 `paimai`


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.customs.gov.cn/`
- `target`: `/customs/list`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: warning\n由于区域限制，建议在国内 IP 的机器上自建\n:::",
  "example": "/gov/customs/list/paimai",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "customs/list.ts",
  "maintainers": [
    "Jeason0228",
    "TonyRL",
    "he1q"
  ],
  "name": "拍卖信息 / 海关法规 / 最新文件",
  "parameters": {
    "gchannel": "支持 `paimai`, `fagui` 及 `latest` 3 个频道，默认为 `paimai`"
  },
  "path": "/customs/list/:gchannel?",
  "radar": [
    {
      "source": [
        "www.customs.gov.cn/"
      ],
      "target": "/customs/list"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.customs.gov.cn/"
}
```
