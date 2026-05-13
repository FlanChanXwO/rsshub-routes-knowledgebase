# bntnews - Category

## Coverage
`index-only`

## Route
- Namespace: `bntnews`
- Namespace Name: `bntnews`
- Route Path: `/:category?`
- Route Name: `Category`
- Example: `/bntnews/bnt003000000`
- URL: `bntnews.co.kr`
- Language: `ko`
- Categories: `new-media`
- Maintainers: `iamsnn`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/bntnews/index.ts')`

## Description
| Beauty | Fashion | Star | Style+ | Photo | Life | Now |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| bnt003000000 | bnt002000000 | bnt004000000 | bnt007000000 | bnt009000000 | bnt005000000 | bnt008000000 |

## Parameters
- `category`: Category ID, see table below, default to Now (bnt008000000)


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
    "new-media"
  ],
  "description": "| Beauty | Fashion | Star | Style+ | Photo | Life | Now |\n| ---- | ---- | ---- | ---- | ---- | ---- | ---- |\n| bnt003000000 | bnt002000000 | bnt004000000 | bnt007000000 | bnt009000000 | bnt005000000 | bnt008000000 |",
  "example": "/bntnews/bnt003000000",
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
    "iamsnn"
  ],
  "module": "() => import('@/routes/bntnews/index.ts')",
  "name": "Category",
  "parameters": {
    "category": "Category ID, see table below, default to Now (bnt008000000)"
  },
  "path": "/:category?"
}
```
