# 特斯拉中国 - 价格

## Coverage
`index-only`

## Route
- Namespace: `tesla`
- Namespace Name: `特斯拉中国`
- Route Path: `/price`
- Route Name: `价格`
- Example: `/tesla/price`
- URL: `tesla.cn/model3/design`
- Language: `zh-CN`
- Categories: `shopping`
- Maintainers: `xiaokyo`
- Source Location: `price/index.ts`
- Source Module: `() => import('@/routes/tesla/price/index.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `tesla.cn/model3/design`
  - `tesla.cn/`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/tesla/price",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "price/index.ts",
  "maintainers": [
    "xiaokyo"
  ],
  "module": "() => import('@/routes/tesla/price/index.ts')",
  "name": "价格",
  "parameters": {},
  "path": "/price",
  "radar": [
    {
      "source": [
        "tesla.cn/model3/design",
        "tesla.cn/"
      ]
    }
  ],
  "url": "tesla.cn/model3/design"
}
```
