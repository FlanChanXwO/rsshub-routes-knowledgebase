# GamerSky - 评测

## Coverage
`index-only`

## Route
- Namespace: `gamersky`
- Namespace Name: `GamerSky`
- Route Path: `/gamersky/review/:type?`
- Route Name: `评测`
- Example: `/gamersky/review/pc`
- URL: `gamersky.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `yy4382`
- Source Location: `review.ts`
- Source Module: `_None_`

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
  "heat": 128,
  "location": "review.ts",
  "maintainers": [
    "yy4382"
  ],
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
  ],
  "topFeeds": [
    {
      "description": "单机 - 游民星空评测 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56355573445982208",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.gamersky.com/review",
      "title": "单机 - 游民星空评测",
      "type": "feed",
      "url": "rsshub://gamersky/review/pc"
    },
    {
      "description": "全部评测 - 游民星空评测 - Powered by RSSHub",
      "errorAt": "2026-07-01T01:55:03.833Z",
      "errorMessage": "[GET] \"https://db2.gamersky.com/LabelJsonpAjax.aspx?jsondata=%7B%22type%22%3A%22updatenodelabel%22%2C%22isCache%22%3Atrue%2C%22cacheTime%22%3A60%2C%22nodeId%22%3A%2220915%22%2C%22isNodeId%22%3A%22true%22%2C%22page%22%3A1%7D\": <no response> fetch failed\n[GET] \"https://db2.gamersky.com/LabelJsonpAjax.aspx?jsondata=%7B%22type%22%3A%22updatenodelabel%22%2C%22isCache%22%3Atrue%2C%22cacheTime%22%3A60%2C%22nodeId%22%3A%2220915%22%2C%22isNodeId%22%3A%22true%22%2C%22page%22%3A1%7D\": <no response> fetch failed\n",
      "id": "73294792620601344",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.gamersky.com/review",
      "title": "全部评测 - 游民星空评测",
      "type": "feed",
      "url": "rsshub://gamersky/review/all"
    }
  ]
}
```
