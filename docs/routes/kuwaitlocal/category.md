# Kuwait Local - Categorised News

## Coverage
`index-only`

## Route
- Namespace: `kuwaitlocal`
- Namespace Name: `Kuwait Local`
- Route Path: `/:category?`
- Route Name: `Categorised News`
- Example: `/kuwaitlocal/article`
- URL: `kuwaitlocal.com/news/latest`
- Language: `en`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/kuwaitlocal/index.ts')`

## Description
_None_

## Parameters
- `category`: Category name, can be found in URL, `latest` by default


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
  - `kuwaitlocal.com/news/categories/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/kuwaitlocal/article",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/kuwaitlocal/index.ts')",
  "name": "Categorised News",
  "parameters": {
    "category": "Category name, can be found in URL, `latest` by default"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "kuwaitlocal.com/news/categories/:category"
      ],
      "target": "/:category"
    }
  ],
  "url": "kuwaitlocal.com/news/latest"
}
```
