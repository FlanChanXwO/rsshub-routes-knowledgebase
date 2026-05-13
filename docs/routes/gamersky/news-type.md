# GamerSky - 资讯

## Coverage
`index-only`

## Route
- Namespace: `gamersky`
- Namespace Name: `GamerSky`
- Route Path: `/news/:type?`
- Route Name: `资讯`
- Example: `/gamersky/news/pc`
- URL: `gamersky.com`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `yy4382`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/gamersky/news.ts')`

## Description
|today|pc|ns|mobile|web|industry|hardware|tech|
|---|---|---|---|---|---|---|---|
|今日推荐|单机电玩|NS|手游|网游|业界|硬件|科技|

## Parameters
- `type`: 资讯类型，见表，默认为 `pc`


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
  - `www.gamersky.com/news`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "|today|pc|ns|mobile|web|industry|hardware|tech|\n|---|---|---|---|---|---|---|---|\n|今日推荐|单机电玩|NS|手游|网游|业界|硬件|科技|\n",
  "example": "/gamersky/news/pc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "yy4382"
  ],
  "module": "() => import('@/routes/gamersky/news.ts')",
  "name": "资讯",
  "parameters": {
    "type": "资讯类型，见表，默认为 `pc`"
  },
  "path": "/news/:type?",
  "radar": [
    {
      "source": [
        "www.gamersky.com/news"
      ],
      "target": "/news"
    }
  ]
}
```
