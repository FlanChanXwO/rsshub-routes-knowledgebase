# CNCF - Category

## Coverage
`index-only`

## Route
- Namespace: `cncf`
- Namespace Name: `CNCF`
- Route Path: `/:cate?`
- Route Name: `Category`
- Example: `/cncf`
- URL: `cncf.io`
- Language: `en`
- Categories: `programming`
- Maintainers: `Fatpandac`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/cncf/index.ts')`

## Description
| Blog | News | Announcements | Reports |
| ---- | ---- | ------------- | ------- |
| blog | news | announcements | reports |

## Parameters
- `cate`: blog by default


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
    "programming"
  ],
  "description": "| Blog | News | Announcements | Reports |\n| ---- | ---- | ------------- | ------- |\n| blog | news | announcements | reports |",
  "example": "/cncf",
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
    "Fatpandac"
  ],
  "module": "() => import('@/routes/cncf/index.ts')",
  "name": "Category",
  "parameters": {
    "cate": "blog by default"
  },
  "path": "/:cate?"
}
```
