# DW Deutsche Welle - News

## Coverage
`index-only`

## Route
- Namespace: `dw`
- Namespace Name: `DW Deutsche Welle`
- Route Path: `/news/:lang?/:id?`
- Route Name: `News`
- Example: `/dw/news`
- URL: `dw.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `quiniapiezoelectricity`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/dw/news.ts')`

## Description
::: tip
Parameters can be obtained from the official website, for instance:
For the site https://www.dw.com/de/deutschland/s-12321 the language code would be `de` and the category ID would be `s-1432`.
:::

## Parameters
- `lang`: Language, see below, default to en
- `id`: Category ID, see below, default to the id of the Top Stories Page of the language chosen


## Features
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `requireConfig`: false

## Radar
### Rule 1
- `source`:
  - `www.dw.com/:lang/:name/:id`
- `target`: `/news/:lang/:id`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "\n::: tip\nParameters can be obtained from the official website, for instance:\nFor the site https://www.dw.com/de/deutschland/s-12321 the language code would be `de` and the category ID would be `s-1432`.\n:::\n",
  "example": "/dw/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "quiniapiezoelectricity"
  ],
  "module": "() => import('@/routes/dw/news.ts')",
  "name": "News",
  "parameters": {
    "id": "Category ID, see below, default to the id of the Top Stories Page of the language chosen",
    "lang": "Language, see below, default to en"
  },
  "path": "/news/:lang?/:id?",
  "radar": [
    {
      "source": [
        "www.dw.com/:lang/:name/:id"
      ],
      "target": "/news/:lang/:id"
    }
  ]
}
```
