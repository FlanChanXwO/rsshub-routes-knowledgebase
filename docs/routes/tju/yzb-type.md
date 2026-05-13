# Tianjin University 天津大学 - Admission Office of Graduate

## Coverage
`index-only`

## Route
- Namespace: `tju`
- Namespace Name: `Tianjin University 天津大学`
- Route Path: `/yzb/:type?`
- Route Name: `Admission Office of Graduate`
- Example: `/tju/yzb/notice`
- URL: `cic.tju.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `SuperPung`
- Source Location: `yzb/index.ts`
- Source Module: `() => import('@/routes/tju/yzb/index.ts')`

## Description
| School-level Notice | Master | Doctor | On-the-job Degree |
| :-----------------: | :----: | :----: | :---------------: |
|        notice       | master | doctor |        job        |

## Parameters
- `type`: default `notice`


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
  "description": "| School-level Notice | Master | Doctor | On-the-job Degree |\n| :-----------------: | :----: | :----: | :---------------: |\n|        notice       | master | doctor |        job        |",
  "example": "/tju/yzb/notice",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "yzb/index.ts",
  "maintainers": [
    "SuperPung"
  ],
  "module": "() => import('@/routes/tju/yzb/index.ts')",
  "name": "Admission Office of Graduate",
  "parameters": {
    "type": "default `notice`"
  },
  "path": "/yzb/:type?"
}
```
