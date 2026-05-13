# 俺の 3D エロ動画 (oreno3d) - Author Search

## Coverage
`index-only`

## Route
- Namespace: `oreno3d`
- Namespace Name: `俺の 3D エロ動画 (oreno3d)`
- Route Path: `/characters/:characterid/:sort/:pagelimit?`
- Route Name: `Author Search`
- Example: `/oreno3d/authors/3189/latest/1`
- URL: `oreno3d.com`
- Language: `ja`
- Categories: `anime`
- Maintainers: `xueli_sherryli`
- Source Location: `main.tsx`
- Source Module: `() => import('@/routes/oreno3d/main.tsx')`

## Description
| favorites | hot | latest | popularity |
| --------- | --- | ------ | ---------- |
| favorites | hot | latest | popularity |

## Parameters
- `authorid`: Author id, can be found in URL
- `sort`: Sort method, see the table above
- `pagelimit`: The maximum number of pages to be crawled, the default is 1


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "| favorites | hot | latest | popularity |\n| --------- | --- | ------ | ---------- |\n| favorites | hot | latest | popularity |",
  "example": "/oreno3d/authors/3189/latest/1",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "main.tsx",
  "maintainers": [
    "xueli_sherryli"
  ],
  "module": "() => import('@/routes/oreno3d/main.tsx')",
  "name": "Author Search",
  "parameters": {
    "authorid": "Author id, can be found in URL",
    "pagelimit": "The maximum number of pages to be crawled, the default is 1",
    "sort": "Sort method, see the table above"
  },
  "path": [
    "/authors/:authorid/:sort/:pagelimit?",
    "/characters/:characterid/:sort/:pagelimit?",
    "/origins/:originid/:sort/:pagelimit?",
    "/search/:keyword/:sort/:pagelimit?",
    "/tags/:tagid/:sort/:pagelimit?"
  ]
}
```
