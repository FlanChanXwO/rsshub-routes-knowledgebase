# VisionIAS - News Today

## Coverage
`index-only`

## Route
- Namespace: `visionias`
- Namespace Name: `VisionIAS`
- Route Path: `/visionias/newsToday/:filter?`
- Route Name: `News Today`
- Example: `/visionias/newsToday`
- URL: `visionias.in`
- Language: `_None_`
- Categories: `study`
- Maintainers: `Rjnishant530`
- Source Location: `news-today.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `filter`: {"default": "latest", "description": "Period to fetch news for the current month. All news for the current month or only the latest", "options": [{"label": "All", "value": "all"}, {"label": "Latest", "value": "latest"}]}


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
  - `visionias.in/current-affairs/news-today`
- `target`: `/newsToday`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "example": "/visionias/newsToday",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news-today.ts",
  "maintainers": [
    "Rjnishant530"
  ],
  "name": "News Today",
  "parameters": {
    "filter": {
      "default": "latest",
      "description": "Period to fetch news for the current month. All news for the current month or only the latest",
      "options": [
        {
          "label": "All",
          "value": "all"
        },
        {
          "label": "Latest",
          "value": "latest"
        }
      ]
    }
  },
  "path": "/newsToday/:filter?",
  "radar": [
    {
      "source": [
        "visionias.in/current-affairs/news-today"
      ],
      "target": "/newsToday"
    }
  ],
  "topFeeds": []
}
```
