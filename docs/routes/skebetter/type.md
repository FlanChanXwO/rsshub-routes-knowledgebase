# Skebetter - Hot

## Coverage
`index-only`

## Route
- Namespace: `skebetter`
- Namespace Name: `Skebetter`
- Route Path: `/:type`
- Route Name: `Hot`
- Example: `/skebetter/hot`
- URL: `skebetter.com`
- Language: `en`
- Categories: `anime`
- Maintainers: `SnowAgar25`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/skebetter/index.ts')`

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
- `title`: `Skebetter - Hot`
- `source`:
  - `skebetter.com`
- `target`: `/hot`
### Rule 2
- `title`: `Skebetter - Week`
- `source`:
  - `skebetter.com`
- `target`: `/week`
### Rule 3
- `title`: `Skebetter - Month`
- `source`:
  - `skebetter.com`
- `target`: `/month`
### Rule 4
- `title`: `Skebetter - Latest`
- `source`:
  - `skebetter.com`
- `target`: `/latest`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "\n| 急上昇 | 週間 | 月間 | 新着 |\n| ----- | ---- | ---- | ---- |\n| hot | week | month| latest |",
  "example": "/skebetter/hot",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "SnowAgar25"
  ],
  "module": "() => import('@/routes/skebetter/index.ts')",
  "name": "Hot",
  "parameters": {
    "type": "Type, see below"
  },
  "path": "/:type",
  "radar": [
    {
      "source": [
        "skebetter.com"
      ],
      "target": "/hot",
      "title": "Skebetter - Hot"
    },
    {
      "source": [
        "skebetter.com"
      ],
      "target": "/week",
      "title": "Skebetter - Week"
    },
    {
      "source": [
        "skebetter.com"
      ],
      "target": "/month",
      "title": "Skebetter - Month"
    },
    {
      "source": [
        "skebetter.com"
      ],
      "target": "/latest",
      "title": "Skebetter - Latest"
    }
  ]
}
```
