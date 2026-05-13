# Tianjin University 天津大学 - College of Intelligence and Computing

## Coverage
`index-only`

## Route
- Namespace: `tju`
- Namespace Name: `Tianjin University 天津大学`
- Route Path: `/cic/:type?`
- Route Name: `College of Intelligence and Computing`
- Example: `/tju/cic/news`
- URL: `cic.tju.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `AlanZeng423, SuperPung`
- Source Location: `cic/index.ts`
- Source Module: `() => import('@/routes/tju/cic/index.ts')`

## Description
| College News | Notification | TJU Forum for CIC |
| :----------: | :----------: | :---------------: |
|     news     | notification |       forum       |

## Parameters
- `type`: default `news`


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
    "university"
  ],
  "description": "| College News | Notification | TJU Forum for CIC |\n| :----------: | :----------: | :---------------: |\n|     news     | notification |       forum       |",
  "example": "/tju/cic/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "cic/index.ts",
  "maintainers": [
    "AlanZeng423",
    "SuperPung"
  ],
  "module": "() => import('@/routes/tju/cic/index.ts')",
  "name": "College of Intelligence and Computing",
  "parameters": {
    "type": "default `news`"
  },
  "path": "/cic/:type?"
}
```
