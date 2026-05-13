# 少女前线 - 情报局

## Coverage
`index-only`

## Route
- Namespace: `gf-cn`
- Namespace Name: `少女前线`
- Route Path: `/news/:category?`
- Route Name: `情报局`
- Example: `/gf-cn/news`
- URL: `sunborngame.com`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/gf-cn/news.ts')`

## Description
| 新闻 | 公告 |
| ---- | ---- |
| 1    | 3    |

## Parameters
- `category`: 分类，见下表，默认为新闻


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
  - `sunborngame.com/:category`
  - `sunborngame.com/`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| 新闻 | 公告 |\n| ---- | ---- |\n| 1    | 3    |",
  "example": "/gf-cn/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/gf-cn/news.ts')",
  "name": "情报局",
  "parameters": {
    "category": "分类，见下表，默认为新闻"
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "sunborngame.com/:category",
        "sunborngame.com/"
      ]
    }
  ]
}
```
