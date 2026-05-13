# GamerSky - 评测

## Coverage
`index-only`

## Route
- Namespace: `gamersky`
- Namespace Name: `GamerSky`
- Route Path: `/review/:type?`
- Route Name: `评测`
- Example: `/gamersky/review/pc`
- URL: `gamersky.com`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `yy4382`
- Source Location: `review.ts`
- Source Module: `() => import('@/routes/gamersky/review.ts')`

## Description
|pc|tv|indie|web|mobile|all|
|---|---|---|---|---|---|
|单机|电视|独立游戏|网游|手游|全部评测|

## Parameters
- `type`: 评测类型，可选值为 `pc`、`tv`、`indie`、`web`、`mobile`、`all`，默认为 `pc`


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
  - `www.gamersky.com/review`
- `target`: `/review`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "|pc|tv|indie|web|mobile|all|\n|---|---|---|---|---|---|\n|单机|电视|独立游戏|网游|手游|全部评测|\n",
  "example": "/gamersky/review/pc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "review.ts",
  "maintainers": [
    "yy4382"
  ],
  "module": "() => import('@/routes/gamersky/review.ts')",
  "name": "评测",
  "parameters": {
    "type": "评测类型，可选值为 `pc`、`tv`、`indie`、`web`、`mobile`、`all`，默认为 `pc`"
  },
  "path": "/review/:type?",
  "radar": [
    {
      "source": [
        "www.gamersky.com/review"
      ],
      "target": "/review"
    }
  ]
}
```
