# 完美世界电竞 - 资讯列表

## Coverage
`index-only`

## Route
- Namespace: `wmpvp`
- Namespace Name: `完美世界电竞`
- Route Path: `/news/:type`
- Route Name: `资讯列表`
- Example: `/wmpvp/news/1`
- URL: `wmpvp.com`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `tssujt`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/wmpvp/index.ts')`

## Description
| DOTA2 | CS2 |
| ----- | --- |
| 1     | 2   |

## Parameters
- `type`: 资讯分类，见下表


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| DOTA2 | CS2 |\n| ----- | --- |\n| 1     | 2   |",
  "example": "/wmpvp/news/1",
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
    "tssujt"
  ],
  "module": "() => import('@/routes/wmpvp/index.ts')",
  "name": "资讯列表",
  "parameters": {
    "type": "资讯分类，见下表"
  },
  "path": "/news/:type"
}
```
