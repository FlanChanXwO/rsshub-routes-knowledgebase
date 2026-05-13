# Phoronix - News & Reviews

## Coverage
`index-only`

## Route
- Namespace: `phoronix`
- Namespace Name: `Phoronix`
- Route Path: `/:category?/:topic?`
- Route Name: `News & Reviews`
- Example: `/phoronix/linux/KDE`
- URL: `phoronix.com`
- Language: `en`
- Categories: `new-media`
- Maintainers: `oppliate, Rongronggg9`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/phoronix/index.ts')`

## Description
_None_

## Parameters
- `category`: Category
- `topic`: Topic. You may find available parameters from their navigator links. E.g. to subscribe to `https://www.phoronix.com/reviews/Operating+Systems`, fill in the path `/phoronix/reviews/Operating+Systems`


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
  - `phoronix.com/:category?/:topic?`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/phoronix/linux/KDE",
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
    "oppliate",
    "Rongronggg9"
  ],
  "module": "() => import('@/routes/phoronix/index.ts')",
  "name": "News & Reviews",
  "parameters": {
    "category": "Category",
    "topic": "Topic. You may find available parameters from their navigator links. E.g. to subscribe to `https://www.phoronix.com/reviews/Operating+Systems`, fill in the path `/phoronix/reviews/Operating+Systems`"
  },
  "path": "/:category?/:topic?",
  "radar": [
    {
      "source": [
        "phoronix.com/:category?/:topic?"
      ]
    }
  ]
}
```
