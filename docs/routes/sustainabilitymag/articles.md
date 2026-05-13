# Sustainability Magazine - Articles

## Coverage
`index-only`

## Route
- Namespace: `sustainabilitymag`
- Namespace Name: `Sustainability Magazine`
- Route Path: `/articles`
- Route Name: `Articles`
- Example: `/sustainabilitymag/articles`
- URL: `sustainabilitymag.com/articles`
- Language: `en`
- Categories: `other`
- Maintainers: `mintyfrankie`
- Source Location: `articles.ts`
- Source Module: `() => import('@/routes/sustainabilitymag/articles.ts')`

## Description
_None_

## Parameters
_None_


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
  - `https://sustainabilitymag.com/articles`
- `target`: `/sustainabilitymag/articles`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/sustainabilitymag/articles",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "articles.ts",
  "maintainers": [
    "mintyfrankie"
  ],
  "module": "() => import('@/routes/sustainabilitymag/articles.ts')",
  "name": "Articles",
  "path": "/articles",
  "radar": [
    {
      "source": [
        "https://sustainabilitymag.com/articles"
      ],
      "target": "/sustainabilitymag/articles"
    }
  ],
  "url": "sustainabilitymag.com/articles"
}
```
