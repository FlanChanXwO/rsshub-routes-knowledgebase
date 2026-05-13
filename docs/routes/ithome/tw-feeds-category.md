# iThome 台灣 - Feeds

## Coverage
`index-only`

## Route
- Namespace: `ithome`
- Namespace Name: `iThome 台灣`
- Route Path: `/tw/feeds/:category`
- Route Name: `Feeds`
- Example: `/ithome/tw/feeds/news`
- URL: `ithome.com`
- Language: `zh-TW`
- Categories: `new-media`
- Maintainers: `miles170`
- Source Location: `tw/feeds.ts`
- Source Module: `() => import('@/routes/ithome/tw/feeds.ts')`

## Description
| 新聞 | AI       | Cloud | DevOps | 資安     |
| ---- | -------- | ----- | ------ | -------- |
| news | big-data | cloud | devops | security |

## Parameters
- `category`: 類別


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
  - `www.ithome.com.tw/:category`
  - `www.ithome.com.tw/:category/feeds`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 新聞 | AI       | Cloud | DevOps | 資安     |\n| ---- | -------- | ----- | ------ | -------- |\n| news | big-data | cloud | devops | security |",
  "example": "/ithome/tw/feeds/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "tw/feeds.ts",
  "maintainers": [
    "miles170"
  ],
  "module": "() => import('@/routes/ithome/tw/feeds.ts')",
  "name": "Feeds",
  "parameters": {
    "category": "類別"
  },
  "path": "/tw/feeds/:category",
  "radar": [
    {
      "source": [
        "www.ithome.com.tw/:category",
        "www.ithome.com.tw/:category/feeds"
      ]
    }
  ]
}
```
