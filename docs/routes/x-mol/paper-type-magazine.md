# X-MOL - Journal

## Coverage
`index-only`

## Route
- Namespace: `x-mol`
- Namespace Name: `X-MOL`
- Route Path: `/paper/:type/:magazine`
- Route Name: `Journal`
- Example: `/x-mol/paper/0/9`
- URL: `x-mol.com`
- Language: `zh-CN`
- Categories: `journal`
- Maintainers: `cssxsh`
- Source Location: `paper.ts`
- Source Module: `() => import('@/routes/x-mol/paper.ts')`

## Description
_None_

## Parameters
- `type`: type
- `magazine`: magazine


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/x-mol/paper/0/9",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "paper.ts",
  "maintainers": [
    "cssxsh"
  ],
  "module": "() => import('@/routes/x-mol/paper.ts')",
  "name": "Journal",
  "parameters": {
    "magazine": "magazine",
    "type": "type"
  },
  "path": "/paper/:type/:magazine"
}
```
