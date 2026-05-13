# 听听 FM - 节目

## Coverage
`index-only`

## Route
- Namespace: `tingtingfm`
- Namespace Name: `听听 FM`
- Route Path: `/program/:programId`
- Route Name: `节目`
- Example: `/tingtingfm/program/M7VJv6Jj4R`
- URL: `mobile.tingtingfm.com`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `TonyRL`
- Source Location: `program.tsx`
- Source Module: `() => import('@/routes/tingtingfm/program.tsx')`

## Description
_None_

## Parameters
- `programId`: 节目 ID，可以在 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `mobile.tingtingfm.com/v3/program/:programId`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/tingtingfm/program/M7VJv6Jj4R",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "location": "program.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/tingtingfm/program.tsx')",
  "name": "节目",
  "parameters": {
    "programId": "节目 ID，可以在 URL 中找到"
  },
  "path": "/program/:programId",
  "radar": [
    {
      "source": [
        "mobile.tingtingfm.com/v3/program/:programId"
      ]
    }
  ],
  "view": 4
}
```
