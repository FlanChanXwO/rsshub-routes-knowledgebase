# Curius - User

## Coverage
`index-only`

## Route
- Namespace: `curius`
- Namespace Name: `Curius`
- Route Path: `/links/:name`
- Route Name: `User`
- Example: `/curius/links/yuu-yuu`
- URL: `curius.app`
- Language: `en`
- Categories: `social-media`
- Maintainers: `Ovler-Young`
- Source Location: `links.tsx`
- Source Module: `() => import('@/routes/curius/links.tsx')`

## Description
_None_

## Parameters
- `name`: Username, can be found in URL


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
  - `curius.app/:name`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/curius/links/yuu-yuu",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "links.tsx",
  "maintainers": [
    "Ovler-Young"
  ],
  "module": "() => import('@/routes/curius/links.tsx')",
  "name": "User",
  "parameters": {
    "name": "Username, can be found in URL"
  },
  "path": "/links/:name",
  "radar": [
    {
      "source": [
        "curius.app/:name"
      ]
    }
  ]
}
```
