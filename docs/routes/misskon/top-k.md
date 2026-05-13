# MissKON - Top k days

## Coverage
`index-only`

## Route
- Namespace: `misskon`
- Namespace Name: `MissKON`
- Route Path: `/top/:k`
- Route Name: `Top k days`
- Example: `/misskon/top/60`
- URL: `misskon.com`
- Language: `en`
- Categories: `picture`
- Maintainers: `Urabartin`
- Source Location: `top.ts`
- Source Module: `() => import('@/routes/misskon/top.ts')`

## Description
_None_

## Parameters
- `k`: Top k days, can be 3, 7, 30 or 60


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `title`: `Top 3 days`
- `source`:
  - `misskon.com/top3/`
- `target`: `/top/3`
### Rule 2
- `title`: `Top 7 days`
- `source`:
  - `misskon.com/top7/`
- `target`: `/top/7`
### Rule 3
- `title`: `Top 30 days`
- `source`:
  - `misskon.com/top30/`
- `target`: `/top/30`
### Rule 4
- `title`: `Top 60 days`
- `source`:
  - `misskon.com/top60/`
- `target`: `/top/60`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/misskon/top/60",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "top.ts",
  "maintainers": [
    "Urabartin"
  ],
  "module": "() => import('@/routes/misskon/top.ts')",
  "name": "Top k days",
  "parameters": {
    "k": "Top k days, can be 3, 7, 30 or 60"
  },
  "path": "/top/:k",
  "radar": [
    {
      "source": [
        "misskon.com/top3/"
      ],
      "target": "/top/3",
      "title": "Top 3 days"
    },
    {
      "source": [
        "misskon.com/top7/"
      ],
      "target": "/top/7",
      "title": "Top 7 days"
    },
    {
      "source": [
        "misskon.com/top30/"
      ],
      "target": "/top/30",
      "title": "Top 30 days"
    },
    {
      "source": [
        "misskon.com/top60/"
      ],
      "target": "/top/60",
      "title": "Top 60 days"
    }
  ]
}
```
