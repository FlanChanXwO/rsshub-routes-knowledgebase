# Skebetter - Manga

## Coverage
`index-only`

## Route
- Namespace: `skebetter`
- Namespace Name: `Skebetter`
- Route Path: `/skebetter/manga/:order`
- Route Name: `Manga`
- Example: `/skebetter/manga/1`
- URL: `skebetter.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `SnowAgar25`
- Source Location: `manga.ts`
- Source Module: `_None_`

## Description
| 新着 (Latest) | 人気 (Hot) |
| ------------- | ---------- |
| 1             | 2          |

## Parameters
- `order`: Order, see below.


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
- `title`: `Manga - Latest`
- `source`:
  - `skebetter.com/series`
- `target`: `/manga/1`
### Rule 2
- `title`: `Manga - Hot`
- `source`:
  - `skebetter.com/series`
- `target`: `/manga/2`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "| 新着 (Latest) | 人気 (Hot) |\n| ------------- | ---------- |\n| 1             | 2          |",
  "example": "/skebetter/manga/1",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "manga.ts",
  "maintainers": [
    "SnowAgar25"
  ],
  "name": "Manga",
  "parameters": {
    "order": "Order, see below."
  },
  "path": "/manga/:order",
  "radar": [
    {
      "source": [
        "skebetter.com/series"
      ],
      "target": "/manga/1",
      "title": "Manga - Latest"
    },
    {
      "source": [
        "skebetter.com/series"
      ],
      "target": "/manga/2",
      "title": "Manga - Hot"
    }
  ],
  "topFeeds": [
    {
      "description": "Skebetter Manga - 人気 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70726183814120448",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://skebetter.com/series?order=2",
      "title": "Skebetter Manga - 人気",
      "type": "feed",
      "url": "rsshub://skebetter/manga/2"
    }
  ]
}
```
