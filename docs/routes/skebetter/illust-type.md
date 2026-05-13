# Skebetter - Illust

## Coverage
`index-only`

## Route
- Namespace: `skebetter`
- Namespace Name: `Skebetter`
- Route Path: `/illust/:type`
- Route Name: `Illust`
- Example: `/skebetter/illust/hot`
- URL: `skebetter.com`
- Language: `en`
- Categories: `anime`
- Maintainers: `SnowAgar25`
- Source Location: `illust.ts`
- Source Module: `() => import('@/routes/skebetter/illust.ts')`

## Description
| 急上昇 | 週間 | 月間 | 新着 |
| ----- | ---- | ---- | ---- |
| hot | week | month| latest |

## Parameters
- `type`: Type, see below


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
- `title`: `Illust - Hot`
- `source`:
  - `skebetter.com/illust`
- `target`: `/illust/hot`
### Rule 2
- `title`: `Illust - Week`
- `source`:
  - `skebetter.com/illust`
- `target`: `/illust/week`
### Rule 3
- `title`: `Illust - Month`
- `source`:
  - `skebetter.com/illust`
- `target`: `/illust/month`
### Rule 4
- `title`: `Illust - Latest`
- `source`:
  - `skebetter.com/illust`
- `target`: `/illust/latest`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "\n| 急上昇 | 週間 | 月間 | 新着 |\n| ----- | ---- | ---- | ---- |\n| hot | week | month| latest |",
  "example": "/skebetter/illust/hot",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "illust.ts",
  "maintainers": [
    "SnowAgar25"
  ],
  "module": "() => import('@/routes/skebetter/illust.ts')",
  "name": "Illust",
  "parameters": {
    "type": "Type, see below"
  },
  "path": "/illust/:type",
  "radar": [
    {
      "source": [
        "skebetter.com/illust"
      ],
      "target": "/illust/hot",
      "title": "Illust - Hot"
    },
    {
      "source": [
        "skebetter.com/illust"
      ],
      "target": "/illust/week",
      "title": "Illust - Week"
    },
    {
      "source": [
        "skebetter.com/illust"
      ],
      "target": "/illust/month",
      "title": "Illust - Month"
    },
    {
      "source": [
        "skebetter.com/illust"
      ],
      "target": "/illust/latest",
      "title": "Illust - Latest"
    }
  ]
}
```
