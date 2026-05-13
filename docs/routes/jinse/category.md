# 金色财经 - 分类

## Coverage
`index-only`

## Route
- Namespace: `jinse`
- Namespace Name: `金色财经`
- Route Path: `/:category?`
- Route Name: `分类`
- Example: `/jinse/zhengce`
- URL: `jinse.com.cn`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `catalogue.ts`
- Source Module: `() => import('@/routes/jinse/catalogue.ts')`

## Description
| 政策    | 行情         | DeFi | 矿业  | 以太坊 2.0 |
| ------- | ------------ | ---- | ----- | ---------- |
| zhengce | fenxishishuo | defi | kuang | 以太坊 2.0 |

| 产业     | IPFS | 技术 | 百科  | 研报          |
| -------- | ---- | ---- | ----- | ------------- |
| industry | IPFS | tech | baike | capitalmarket |

## Parameters
- `category`: 分类，见下表，默认为政策


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
    "finance"
  ],
  "description": "| 政策    | 行情         | DeFi | 矿业  | 以太坊 2.0 |\n| ------- | ------------ | ---- | ----- | ---------- |\n| zhengce | fenxishishuo | defi | kuang | 以太坊 2.0 |\n\n| 产业     | IPFS | 技术 | 百科  | 研报          |\n| -------- | ---- | ---- | ----- | ------------- |\n| industry | IPFS | tech | baike | capitalmarket |",
  "example": "/jinse/zhengce",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "catalogue.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/jinse/catalogue.ts')",
  "name": "分类",
  "parameters": {
    "category": "分类，见下表，默认为政策"
  },
  "path": "/:category?"
}
```
