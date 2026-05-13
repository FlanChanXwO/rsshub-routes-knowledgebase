# swissinfo - Category

## Coverage
`index-only`

## Route
- Namespace: `swissinfo`
- Namespace Name: `swissinfo`
- Route Path: `/:language?/:category?`
- Route Name: `Category`
- Example: `/swissinfo/eng/latest-news`
- URL: `swissinfo.ch`
- Language: `en`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/swissinfo/index.ts')`

## Description
_None_

## Parameters
- `language`: Language, eng by default
- `category`: Category, Latest News by default


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
  - `swissinfo.ch/:language/:category`
  - `swissinfo.ch/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/swissinfo/eng/latest-news",
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
    "nczitzk"
  ],
  "module": "() => import('@/routes/swissinfo/index.ts')",
  "name": "Category",
  "parameters": {
    "category": "Category, Latest News by default",
    "language": "Language, eng by default"
  },
  "path": "/:language?/:category?",
  "radar": [
    {
      "source": [
        "swissinfo.ch/:language/:category",
        "swissinfo.ch/"
      ]
    }
  ]
}
```
