# Prime Minister of Canada - News

## Coverage
`index-only`

## Route
- Namespace: `gc.ca`
- Namespace Name: `Prime Minister of Canada`
- Route Path: `/pm/:language?`
- Route Name: `News`
- Example: `/gc.ca/pm/en`
- URL: `pm.gc.ca`
- Language: `en`
- Categories: `government`
- Maintainers: `elibroftw`
- Source Location: `pm-news.ts`
- Source Module: `() => import('@/routes/gc.ca/pm-news.ts')`

## Description
_None_

## Parameters
- `language`: Language (en or fr)


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
  - `pm.gc.ca`
  - `pm.gc.ca/:language`
  - `pm.gc.ca/:language/news`
  - `pm.gc.ca/:language/nouvelles`
- `target`: `/pm/:language`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/gc.ca/pm/en",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "pm-news.ts",
  "maintainers": [
    "elibroftw"
  ],
  "module": "() => import('@/routes/gc.ca/pm-news.ts')",
  "name": "News",
  "parameters": {
    "language": "Language (en or fr)"
  },
  "path": "/pm/:language?",
  "radar": [
    {
      "source": [
        "pm.gc.ca",
        "pm.gc.ca/:language",
        "pm.gc.ca/:language/news",
        "pm.gc.ca/:language/nouvelles"
      ],
      "target": "/pm/:language"
    }
  ]
}
```
