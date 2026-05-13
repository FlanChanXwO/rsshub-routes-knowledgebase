# Alto - Toronto-Québec City High-Speed Rail Network - Alto News

## Coverage
`index-only`

## Route
- Namespace: `altotrain`
- Namespace Name: `Alto - Toronto-Québec City High-Speed Rail Network`
- Route Path: `/:language?`
- Route Name: `Alto News`
- Example: `/altotrain/en`
- URL: `altotrain.ca`
- Language: `en`
- Categories: `travel`
- Maintainers: `elibroftw`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/altotrain/news.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `altotrain.ca/:language`
  - `altotrain.ca/:language/news`
  - `altotrain.ca/:language/nouvelles`
- `target`: `/:language`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/altotrain/en",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "elibroftw"
  ],
  "module": "() => import('@/routes/altotrain/news.ts')",
  "name": "Alto News",
  "path": "/:language?",
  "radar": [
    {
      "source": [
        "altotrain.ca/:language",
        "altotrain.ca/:language/news",
        "altotrain.ca/:language/nouvelles"
      ],
      "target": "/:language"
    }
  ]
}
```
