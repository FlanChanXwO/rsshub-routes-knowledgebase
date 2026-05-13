# MSN - News

## Coverage
`index-only`

## Route
- Namespace: `msn`
- Namespace Name: `MSN`
- Route Path: `/:market/:name/:id`
- Route Name: `News`
- Example: `/zh-tw/Bloomberg/sr-vid-08gw7ky4u229xjsjvnf4n6n7v67gxm0pjmv9fr4y2x9jjmwcri4s`
- URL: `msn.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `KTachibanaM`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/msn/index.ts')`

## Description
MSN News

## Parameters
- `market`: Market code. Find it in MSN url, e.g. zh-tw
- `name`: Name of the channel. Find it in MSN url, e.g. Bloomberg
- `id`: ID of the channel (always starts with sr-vid). Find it in MSN url, e.g. sr-vid-08gw7ky4u229xjsjvnf4n6n7v67gxm0pjmv9fr4y2x9jjmwcri4s


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `www.msn.com/:market/channel/source/:name/:id`
- `target`: `/:market/:name/:id`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "MSN News",
  "example": "/zh-tw/Bloomberg/sr-vid-08gw7ky4u229xjsjvnf4n6n7v67gxm0pjmv9fr4y2x9jjmwcri4s",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportRadar": true
  },
  "location": "index.ts",
  "maintainers": [
    "KTachibanaM"
  ],
  "module": "() => import('@/routes/msn/index.ts')",
  "name": "News",
  "parameters": {
    "id": "ID of the channel (always starts with sr-vid). Find it in MSN url, e.g. sr-vid-08gw7ky4u229xjsjvnf4n6n7v67gxm0pjmv9fr4y2x9jjmwcri4s",
    "market": "Market code. Find it in MSN url, e.g. zh-tw",
    "name": "Name of the channel. Find it in MSN url, e.g. Bloomberg"
  },
  "path": "/:market/:name/:id",
  "radar": [
    {
      "source": [
        "www.msn.com/:market/channel/source/:name/:id"
      ],
      "target": "/:market/:name/:id"
    }
  ]
}
```
