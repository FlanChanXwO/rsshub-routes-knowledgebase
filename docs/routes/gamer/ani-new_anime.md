# 巴哈姆特電玩資訊站 - 動畫瘋 - 最後更新

## Coverage
`index-only`

## Route
- Namespace: `gamer`
- Namespace Name: `巴哈姆特電玩資訊站`
- Route Path: `/ani/new_anime`
- Route Name: `動畫瘋 - 最後更新`
- Example: `/gamer/ani/new_anime`
- URL: `ani.gamer.com.tw/`
- Language: `zh-TW`
- Categories: `anime`
- Maintainers: `maple3142, pseudoyu`
- Source Location: `ani/new-anime.ts`
- Source Module: `() => import('@/routes/gamer/ani/new-anime.ts')`

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
  - `ani.gamer.com.tw/`
- `target`: `/new_anime`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/gamer/ani/new_anime",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "ani/new-anime.ts",
  "maintainers": [
    "maple3142",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/gamer/ani/new-anime.ts')",
  "name": "動畫瘋 - 最後更新",
  "parameters": {},
  "path": "/ani/new_anime",
  "radar": [
    {
      "source": [
        "ani.gamer.com.tw/"
      ],
      "target": "/new_anime"
    }
  ],
  "url": "ani.gamer.com.tw/",
  "view": 3
}
```
