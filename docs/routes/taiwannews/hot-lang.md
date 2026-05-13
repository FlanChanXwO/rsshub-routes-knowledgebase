# Taiwan News - Hot News

## Coverage
`index-only`

## Route
- Namespace: `taiwannews`
- Namespace Name: `Taiwan News`
- Route Path: `/hot/:lang?`
- Route Name: `Hot News`
- Example: `/taiwannews/hot`
- URL: `taiwannews.com.tw`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `hot.ts`
- Source Module: `() => import('@/routes/taiwannews/hot.ts')`

## Description
_None_

## Parameters
- `lang`: Language, `en` or `zh`, `en` by default


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
  - `taiwannews.com.tw/:lang/index`
- `target`: `/hot/:lang`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/taiwannews/hot",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "hot.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/taiwannews/hot.ts')",
  "name": "Hot News",
  "parameters": {
    "lang": "Language, `en` or `zh`, `en` by default"
  },
  "path": "/hot/:lang?",
  "radar": [
    {
      "source": [
        "taiwannews.com.tw/:lang/index"
      ],
      "target": "/hot/:lang"
    }
  ]
}
```
