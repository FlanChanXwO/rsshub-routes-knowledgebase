# DailyPush - All

## Coverage
`index-only`

## Route
- Namespace: `dailypush`
- Namespace Name: `DailyPush`
- Route Path: `/:sort?`
- Route Name: `All`
- Example: `/dailypush/latest`
- URL: `dailypush.dev`
- Language: `en`
- Categories: `programming`
- Maintainers: `TheGeeKing`
- Source Location: `all.ts`
- Source Module: `() => import('@/routes/dailypush/all.ts')`

## Description
_None_

## Parameters
- `sort`: {"default": "", "description": "Sort order: `` (trending, default) or `latest`", "options": [{"label": "Trending", "value": ""}, {"label": "Latest", "value": "latest"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `dailypush.dev/`
  - `dailypush.dev/latest`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/dailypush/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "all.ts",
  "maintainers": [
    "TheGeeKing"
  ],
  "module": "() => import('@/routes/dailypush/all.ts')",
  "name": "All",
  "parameters": {
    "sort": {
      "default": "",
      "description": "Sort order: `` (trending, default) or `latest`",
      "options": [
        {
          "label": "Trending",
          "value": ""
        },
        {
          "label": "Latest",
          "value": "latest"
        }
      ]
    }
  },
  "path": "/:sort?",
  "radar": [
    {
      "source": [
        "dailypush.dev/",
        "dailypush.dev/latest"
      ],
      "target": "/"
    }
  ]
}
```
