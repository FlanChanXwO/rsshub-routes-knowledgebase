# Skebetter - Illust

## Coverage
`index-only`

## Route
- Namespace: `skebetter`
- Namespace Name: `Skebetter`
- Route Path: `/skebetter/illust/:type`
- Route Name: `Illust`
- Example: `/skebetter/illust/hot`
- URL: `skebetter.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `SnowAgar25`
- Source Location: `illust.ts`
- Source Module: `_None_`

## Description
| 急上昇 | 週間 | 月間  | 新着   |
| ------ | ---- | ----- | ------ |
| hot    | week | month | latest |

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
  "description": "| 急上昇 | 週間 | 月間  | 新着   |\n| ------ | ---- | ----- | ------ |\n| hot    | week | month | latest |",
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
  "heat": 10,
  "location": "illust.ts",
  "maintainers": [
    "SnowAgar25"
  ],
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
  ],
  "topFeeds": [
    {
      "description": "Skebetter Illust - 急上昇 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70005697760697344",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://skebetter.com/illust",
      "title": "Skebetter Illust - 急上昇",
      "type": "feed",
      "url": "rsshub://skebetter/illust/hot"
    },
    {
      "description": "Skebetter Illust - 月間 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70758560507674624",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://skebetter.com/illust?term=month",
      "title": "Skebetter Illust - 月間",
      "type": "feed",
      "url": "rsshub://skebetter/illust/month"
    }
  ]
}
```
