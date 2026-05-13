# MyFigureCollection - 圖片

## Coverage
`index-only`

## Route
- Namespace: `myfigurecollection`
- Namespace Name: `MyFigureCollection`
- Route Path: `/:category?/:language?`
- Route Name: `圖片`
- Example: `/myfigurecollection/potd`
- URL: `zh.myfigurecollection.net/browse`
- Language: `en`
- Categories: `shopping`
- Maintainers: `nczitzk`
- Source Location: `index.tsx`
- Source Module: `() => import('@/routes/myfigurecollection/index.tsx')`

## Description
| 每日圖片 | 每週圖片 | 每月圖片 |
| -------- | -------- | -------- |
| potd     | potw     | potm     |

## Parameters
- `category`: 分类，默认为每日圖片
- `language`: 语言，见上表，默认为空，即 `en`


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
  - `zh.myfigurecollection.net/browse`
  - `zh.myfigurecollection.net/`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "| 每日圖片 | 每週圖片 | 每月圖片 |\n| -------- | -------- | -------- |\n| potd     | potw     | potm     |",
  "example": "/myfigurecollection/potd",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/myfigurecollection/index.tsx')",
  "name": "圖片",
  "parameters": {
    "category": "分类，默认为每日圖片",
    "language": "语言，见上表，默认为空，即 `en`"
  },
  "path": "/:category?/:language?",
  "radar": [
    {
      "source": [
        "zh.myfigurecollection.net/browse",
        "zh.myfigurecollection.net/"
      ]
    }
  ],
  "url": "zh.myfigurecollection.net/browse"
}
```
