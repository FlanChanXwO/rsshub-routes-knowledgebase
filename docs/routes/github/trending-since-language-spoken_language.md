# GitHub - Trending

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/trending/:since/:language/:spoken_language?`
- Route Name: `Trending`
- Example: `/github/trending/daily/javascript/en`
- URL: `github.com/trending`
- Language: `en`
- Categories: `programming`
- Maintainers: `DIYgod, jameschensmith`
- Source Location: `trending.tsx`
- Source Module: `() => import('@/routes/github/trending.tsx')`

## Description
_None_

## Parameters
- `since`: {"description": "time range", "options": [{"label": "Today", "value": "daily"}, {"label": "This week", "value": "weekly"}, {"label": "This month", "value": "monthly"}]}
- `language`: {"default": "any", "description": "the feed language, available in [Trending page](https://github.com/trending/javascript?since=monthly) 's URL, don't filter option is `any`"}
- `spoken_language`: {"description": "natural language, available in [Trending page](https://github.com/trending/javascript?since=monthly) 's URL"}


## Features
- `requireConfig`: [{"description": "", "name": "GITHUB_ACCESS_TOKEN"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `github.com/trending`
- `target`: `/trending/:since`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/github/trending/daily/javascript/en",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "GITHUB_ACCESS_TOKEN"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "trending.tsx",
  "maintainers": [
    "DIYgod",
    "jameschensmith"
  ],
  "module": "() => import('@/routes/github/trending.tsx')",
  "name": "Trending",
  "parameters": {
    "language": {
      "default": "any",
      "description": "the feed language, available in [Trending page](https://github.com/trending/javascript?since=monthly) 's URL, don't filter option is `any`"
    },
    "since": {
      "description": "time range",
      "options": [
        {
          "label": "Today",
          "value": "daily"
        },
        {
          "label": "This week",
          "value": "weekly"
        },
        {
          "label": "This month",
          "value": "monthly"
        }
      ]
    },
    "spoken_language": {
      "description": "natural language, available in [Trending page](https://github.com/trending/javascript?since=monthly) 's URL"
    }
  },
  "path": "/trending/:since/:language/:spoken_language?",
  "radar": [
    {
      "source": [
        "github.com/trending"
      ],
      "target": "/trending/:since"
    }
  ],
  "url": "github.com/trending",
  "view": 5
}
```
