# GoCN - 招聘

## Coverage
`index-only`

## Route
- Namespace: `gocn`
- Namespace Name: `GoCN`
- Route Path: `/jobs`
- Route Name: `招聘`
- Example: `/gocn/jobs`
- URL: `gocn.vip/`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `AtlanCI, CcccFz`
- Source Location: `jobs.ts`
- Source Module: `() => import('@/routes/gocn/jobs.ts')`

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
  - `gocn.vip/`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/gocn/jobs",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jobs.ts",
  "maintainers": [
    "AtlanCI",
    "CcccFz"
  ],
  "module": "() => import('@/routes/gocn/jobs.ts')",
  "name": "招聘",
  "parameters": {},
  "path": "/jobs",
  "radar": [
    {
      "source": [
        "gocn.vip/"
      ]
    }
  ],
  "url": "gocn.vip/"
}
```
