# CnGal - 制作者 / 游戏新闻

## Coverage
`index-only`

## Route
- Namespace: `cngal`
- Namespace Name: `CnGal`
- Route Path: `/entry/:id`
- Route Name: `制作者 / 游戏新闻`
- Example: `/cngal/entry/2693`
- URL: `www.cngal.org`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `kmod-midori`
- Source Location: `entry.tsx`
- Source Module: `() => import('@/routes/cngal/entry.tsx')`

## Description
_None_

## Parameters
- `id`: 词条ID，游戏或制作者页面URL的最后一串数字


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
  - `www.cngal.org/entries/index/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/cngal/entry/2693",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "entry.tsx",
  "maintainers": [
    "kmod-midori"
  ],
  "module": "() => import('@/routes/cngal/entry.tsx')",
  "name": "制作者 / 游戏新闻",
  "parameters": {
    "id": "词条ID，游戏或制作者页面URL的最后一串数字"
  },
  "path": "/entry/:id",
  "radar": [
    {
      "source": [
        "www.cngal.org/entries/index/:id"
      ]
    }
  ]
}
```
