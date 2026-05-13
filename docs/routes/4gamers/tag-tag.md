# 4Gamers - 标签

## Coverage
`index-only`

## Route
- Namespace: `4gamers`
- Namespace Name: `4Gamers`
- Route Path: `/tag/:tag`
- Route Name: `标签`
- Example: `/4gamers/tag/限時免費`
- URL: `www.4gamers.com.tw/news`
- Language: `zh-TW`
- Categories: `game`
- Maintainers: `hoilc`
- Source Location: `tag.ts`
- Source Module: `() => import('@/routes/4gamers/tag.ts')`

## Description
_None_

## Parameters
- `tag`: 标签名，可在标签 URL 中找到


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
  - `www.4gamers.com.tw/news/tag/:tag`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/4gamers/tag/限時免費",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "tag.ts",
  "maintainers": [
    "hoilc"
  ],
  "module": "() => import('@/routes/4gamers/tag.ts')",
  "name": "标签",
  "parameters": {
    "tag": "标签名，可在标签 URL 中找到"
  },
  "path": "/tag/:tag",
  "radar": [
    {
      "source": [
        "www.4gamers.com.tw/news/tag/:tag"
      ]
    }
  ],
  "url": "www.4gamers.com.tw/news"
}
```
