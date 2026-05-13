# 巴哈姆特電玩資訊站 - 動畫瘋 - 動畫

## Coverage
`index-only`

## Route
- Namespace: `gamer`
- Namespace Name: `巴哈姆特電玩資訊站`
- Route Path: `/ani/anime/:sn`
- Route Name: `動畫瘋 - 動畫`
- Example: `/gamer/ani/anime/36868`
- URL: `acg.gamer.com.tw`
- Language: `zh-TW`
- Categories: `anime`
- Maintainers: `maple3142, pseudoyu`
- Source Location: `ani/anime.ts`
- Source Module: `() => import('@/routes/gamer/ani/anime.ts')`

## Description
_None_

## Parameters
- `sn`: 動畫 sn，在 URL 可以找到


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
- `target`: `/anime/:sn`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/gamer/ani/anime/36868",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "ani/anime.ts",
  "maintainers": [
    "maple3142",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/gamer/ani/anime.ts')",
  "name": "動畫瘋 - 動畫",
  "parameters": {
    "sn": "動畫 sn，在 URL 可以找到"
  },
  "path": "/ani/anime/:sn",
  "radar": [
    {
      "source": [
        "ani.gamer.com.tw/"
      ],
      "target": "/anime/:sn"
    }
  ],
  "view": 3
}
```
