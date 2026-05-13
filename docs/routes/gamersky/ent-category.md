# GamerSky - 娱乐

## Coverage
`index-only`

## Route
- Namespace: `gamersky`
- Namespace Name: `GamerSky`
- Route Path: `/ent/:category?`
- Route Name: `娱乐`
- Example: `/gamersky/ent/xz`
- URL: `gamersky.com`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `LogicJake`
- Source Location: `ent.ts`
- Source Module: `() => import('@/routes/gamersky/ent.ts')`

## Description
|
|
|

## Parameters
- `type`: 分类类型，留空为 `all`


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
  "description": "|\n|\n|\n",
  "example": "/gamersky/ent/xz",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "ent.ts",
  "maintainers": [
    "LogicJake"
  ],
  "module": "() => import('@/routes/gamersky/ent.ts')",
  "name": "娱乐",
  "parameters": {
    "type": "分类类型，留空为 `all`"
  },
  "path": "/ent/:category?",
  "radar": []
}
```
