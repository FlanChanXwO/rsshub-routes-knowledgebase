# 故事 FM - 播客

## Coverage
`index-only`

## Route
- Namespace: `storyfm`
- Namespace Name: `故事 FM`
- Route Path: `/episodes`
- Route Name: `播客`
- Example: `/storyfm/episodes`
- URL: `storyfm.cn/episodes-list`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `episodes.tsx`
- Source Module: `() => import('@/routes/storyfm/episodes.tsx')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `storyfm.cn/episodes-list`
  - `storyfm.cn/`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/storyfm/episodes",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "location": "episodes.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/storyfm/episodes.tsx')",
  "name": "播客",
  "parameters": {},
  "path": "/episodes",
  "radar": [
    {
      "source": [
        "storyfm.cn/episodes-list",
        "storyfm.cn/"
      ]
    }
  ],
  "url": "storyfm.cn/episodes-list"
}
```
