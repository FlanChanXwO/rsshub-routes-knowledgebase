# DailyPush - Tag

## Coverage
`index-only`

## Route
- Namespace: `dailypush`
- Namespace Name: `DailyPush`
- Route Path: `/tag/:tag/:sort?`
- Route Name: `Tag`
- Example: `/dailypush/tag/backend/trending`
- URL: `dailypush.dev`
- Language: `en`
- Categories: `programming`
- Maintainers: `TheGeeKing`
- Source Location: `tags.ts`
- Source Module: `() => import('@/routes/dailypush/tags.ts')`

## Description
_None_

## Parameters
- `tag`: {"description": "Tag name"}
- `sort`: {"default": "trending", "description": "Sort order: `trending` (default) or `latest`", "options": [{"label": "Trending", "value": "trending"}, {"label": "Latest", "value": "latest"}]}


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
  - `dailypush.dev/:tag/trending`
  - `dailypush.dev/:tag/latest`
  - `dailypush.dev/:tag`
- `target`: `/tag/:tag/:sort?`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/dailypush/tag/backend/trending",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "tags.ts",
  "maintainers": [
    "TheGeeKing"
  ],
  "module": "() => import('@/routes/dailypush/tags.ts')",
  "name": "Tag",
  "parameters": {
    "sort": {
      "default": "trending",
      "description": "Sort order: `trending` (default) or `latest`",
      "options": [
        {
          "label": "Trending",
          "value": "trending"
        },
        {
          "label": "Latest",
          "value": "latest"
        }
      ]
    },
    "tag": {
      "description": "Tag name"
    }
  },
  "path": "/tag/:tag/:sort?",
  "radar": [
    {
      "source": [
        "dailypush.dev/:tag/trending",
        "dailypush.dev/:tag/latest",
        "dailypush.dev/:tag"
      ],
      "target": "/tag/:tag/:sort?"
    }
  ]
}
```
