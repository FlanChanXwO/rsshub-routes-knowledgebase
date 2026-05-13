# Foresight News - 专栏

## Coverage
`index-only`

## Route
- Namespace: `foresightnews`
- Namespace Name: `Foresight News`
- Route Path: `/column/:id`
- Route Name: `专栏`
- Example: `/foresightnews/column/1`
- URL: `foresightnews.pro/`
- Language: `en`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `column.ts`
- Source Module: `() => import('@/routes/foresightnews/column.ts')`

## Description
_None_

## Parameters
- `id`: 专栏 id, 可在对应专栏页 URL 中找到


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
  - `foresightnews.pro/column/detail/:id`
  - `foresightnews.pro/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/foresightnews/column/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "column.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/foresightnews/column.ts')",
  "name": "专栏",
  "parameters": {
    "id": "专栏 id, 可在对应专栏页 URL 中找到"
  },
  "path": "/column/:id",
  "radar": [
    {
      "source": [
        "foresightnews.pro/column/detail/:id",
        "foresightnews.pro/"
      ]
    }
  ],
  "url": "foresightnews.pro/"
}
```
