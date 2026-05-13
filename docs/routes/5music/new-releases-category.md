# 五大唱片 - 新貨上架

## Coverage
`index-only`

## Route
- Namespace: `5music`
- Namespace Name: `五大唱片`
- Route Path: `/new-releases/:category?`
- Route Name: `新貨上架`
- Example: `/5music/new-releases`
- URL: `www.5music.com.tw/New_releases.asp`
- Language: `zh-TW`
- Categories: `shopping`
- Maintainers: `gideonsenku`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/5music/index.ts')`

## Description
Categories:
| 華語 | 西洋 | 東洋 | 韓語 | 古典 |
| ---- | ---- | ---- | ---- | ---- |
| A | B | F | M | D |

## Parameters
- `category`: Category, see below, defaults to all


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
  - `www.5music.com.tw/New_releases.asp`
  - `www.5music.com.tw/`
- `target`: `/new-releases`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "Categories:\n| 華語 | 西洋 | 東洋 | 韓語 | 古典 |\n| ---- | ---- | ---- | ---- | ---- |\n| A | B | F | M | D |",
  "example": "/5music/new-releases",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "gideonsenku"
  ],
  "module": "() => import('@/routes/5music/index.ts')",
  "name": "新貨上架",
  "parameters": {
    "category": "Category, see below, defaults to all"
  },
  "path": "/new-releases/:category?",
  "radar": [
    {
      "source": [
        "www.5music.com.tw/New_releases.asp",
        "www.5music.com.tw/"
      ],
      "target": "/new-releases"
    }
  ],
  "url": "www.5music.com.tw/New_releases.asp"
}
```
