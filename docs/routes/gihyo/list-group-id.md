# gihyo.jp - Series

## Coverage
`index-only`

## Route
- Namespace: `gihyo`
- Namespace Name: `gihyo.jp`
- Route Path: `/list/group/:id`
- Route Name: `Series`
- Example: `/gihyo/list/group/Ubuntu-Weekly-Recipe`
- URL: `gihyo.jp`
- Language: `ja`
- Categories: `programming`
- Maintainers: `masakichi`
- Source Location: `group.ts`
- Source Module: `() => import('@/routes/gihyo/group.ts')`

## Description
_None_

## Parameters
- `id`: Series


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
  - `gihyo.jp/list/group/:id`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/gihyo/list/group/Ubuntu-Weekly-Recipe",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "group.ts",
  "maintainers": [
    "masakichi"
  ],
  "module": "() => import('@/routes/gihyo/group.ts')",
  "name": "Series",
  "parameters": {
    "id": "Series"
  },
  "path": "/list/group/:id",
  "radar": [
    {
      "source": [
        "gihyo.jp/list/group/:id"
      ]
    }
  ]
}
```
