# 华尔街见闻 - 实时快讯

## Coverage
`index-only`

## Route
- Namespace: `wallstreetcn`
- Namespace Name: `华尔街见闻`
- Route Path: `/live/:category?/:score?`
- Route Name: `实时快讯`
- Example: `/wallstreetcn/live`
- URL: `wallstreetcn.com`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `live.tsx`
- Source Module: `() => import('@/routes/wallstreetcn/live.tsx')`

## Description
| 要闻   | A 股    | 美股     | 港股     | 外汇  | 商品      | 理财      |
| ------ | ------- | -------- | -------- | ----- | --------- | --------- |
| global | a-stock | us-stock | hk-stock | forex | commodity | financing |

## Parameters
- `category`: 快讯分类，默认`global`，见下表
- `score`: 快讯重要度，默认`1`全部快讯，可设置为`2`只看重要的


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
  - `wallstreetcn.com/live/:category`
  - `wallstreetcn.com/`
- `target`: `/live/:category?`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| 要闻   | A 股    | 美股     | 港股     | 外汇  | 商品      | 理财      |\n| ------ | ------- | -------- | -------- | ----- | --------- | --------- |\n| global | a-stock | us-stock | hk-stock | forex | commodity | financing |",
  "example": "/wallstreetcn/live",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "live.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/wallstreetcn/live.tsx')",
  "name": "实时快讯",
  "parameters": {
    "category": "快讯分类，默认`global`，见下表",
    "score": "快讯重要度，默认`1`全部快讯，可设置为`2`只看重要的"
  },
  "path": "/live/:category?/:score?",
  "radar": [
    {
      "source": [
        "wallstreetcn.com/live/:category",
        "wallstreetcn.com/"
      ],
      "target": "/live/:category?"
    }
  ]
}
```
