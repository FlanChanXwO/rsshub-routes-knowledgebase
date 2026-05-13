# MacMenuBar - Recently

## Coverage
`index-only`

## Route
- Namespace: `macmenubar`
- Namespace Name: `MacMenuBar`
- Route Path: `/recently/:category?`
- Route Name: `Recently`
- Example: `/macmenubar/recently/developer-apps,system-tools`
- URL: `macmenubar.com`
- Language: `en`
- Categories: `blog`
- Maintainers: `5upernova-heng`
- Source Location: `recently.ts`
- Source Module: `() => import('@/routes/macmenubar/recently.ts')`

## Description
_None_

## Parameters
- `category`: Category path name, seperate by comma, default is all categories. Category path name can be found in url


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/macmenubar/recently/developer-apps,system-tools",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "recently.ts",
  "maintainers": [
    "5upernova-heng"
  ],
  "module": "() => import('@/routes/macmenubar/recently.ts')",
  "name": "Recently",
  "parameters": {
    "category": "Category path name, seperate by comma, default is all categories. Category path name can be found in url"
  },
  "path": "/recently/:category?"
}
```
