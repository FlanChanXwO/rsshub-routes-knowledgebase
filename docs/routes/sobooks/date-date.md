# SoBooks - 归档

## Coverage
`index-only`

## Route
- Namespace: `sobooks`
- Namespace Name: `SoBooks`
- Route Path: `/date/:date?`
- Route Name: `归档`
- Example: `/sobooks/date/2020-11`
- URL: `sobooks.net`
- Language: `en`
- Categories: `reading`
- Maintainers: `nczitzk`
- Source Location: `date.ts`
- Source Module: `() => import('@/routes/sobooks/date.ts')`

## Description
_None_

## Parameters
- `date`: 日期，见例子，默认为当前年月


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
  - `sobooks.net/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/sobooks/date/2020-11",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "date.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/sobooks/date.ts')",
  "name": "归档",
  "parameters": {
    "date": "日期，见例子，默认为当前年月"
  },
  "path": "/date/:date?",
  "radar": [
    {
      "source": [
        "sobooks.net/:category"
      ],
      "target": "/:category"
    }
  ]
}
```
