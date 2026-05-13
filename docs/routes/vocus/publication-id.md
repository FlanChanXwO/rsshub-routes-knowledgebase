# 方格子 - 出版專題

## Coverage
`index-only`

## Route
- Namespace: `vocus`
- Namespace Name: `方格子`
- Route Path: `/publication/:id`
- Route Name: `出版專題`
- Example: `/vocus/publication/bass`
- URL: `vocus.cc`
- Language: `zh-TW`
- Categories: `social-media`
- Maintainers: `Maecenas`
- Source Location: `publication.ts`
- Source Module: `() => import('@/routes/vocus/publication.ts')`

## Description
_None_

## Parameters
- `id`: 出版專題 id，可在出版專題主页的 URL 找到


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
  - `vocus.cc/:id/home`
  - `vocus.cc/:id/introduce`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/vocus/publication/bass",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "publication.ts",
  "maintainers": [
    "Maecenas"
  ],
  "module": "() => import('@/routes/vocus/publication.ts')",
  "name": "出版專題",
  "parameters": {
    "id": "出版專題 id，可在出版專題主页的 URL 找到"
  },
  "path": "/publication/:id",
  "radar": [
    {
      "source": [
        "vocus.cc/:id/home",
        "vocus.cc/:id/introduce"
      ]
    }
  ]
}
```
