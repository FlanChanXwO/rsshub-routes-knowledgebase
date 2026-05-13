# Eventernote - 声优活动及演唱会

## Coverage
`index-only`

## Route
- Namespace: `eventernote`
- Namespace Name: `Eventernote`
- Route Path: `/actors/:name/:id`
- Route Name: `声优活动及演唱会`
- Example: `/eventernote/actors/三森すずこ/2634`
- URL: `www.eventernote.com`
- Language: `ja`
- Categories: `anime`
- Maintainers: `KTachibanaM`
- Source Location: `actors.ts`
- Source Module: `() => import('@/routes/eventernote/actors.ts')`

## Description
_None_

## Parameters
- `name`: 声优姓名
- `id`: 声优 ID


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
  - `www.eventernote.com/actors/:name/:id`
  - `www.eventernote.com/actors/:name/:id/events`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/eventernote/actors/三森すずこ/2634",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "actors.ts",
  "maintainers": [
    "KTachibanaM"
  ],
  "module": "() => import('@/routes/eventernote/actors.ts')",
  "name": "声优活动及演唱会",
  "parameters": {
    "id": "声优 ID",
    "name": "声优姓名"
  },
  "path": "/actors/:name/:id",
  "radar": [
    {
      "source": [
        "www.eventernote.com/actors/:name/:id",
        "www.eventernote.com/actors/:name/:id/events"
      ]
    }
  ],
  "view": 3
}
```
