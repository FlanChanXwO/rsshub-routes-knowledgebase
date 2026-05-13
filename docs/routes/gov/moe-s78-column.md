# 国家能源局 - 司局通知

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/moe/s78/:column`
- Route Name: `司局通知`
- Example: `/gov/moe/s78/A13`
- URL: `www.nea.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `TonyRL`
- Source Location: `moe/s78.ts`
- Source Module: `() => import('@/routes/gov/moe/s78.ts')`

## Description
_None_

## Parameters
- `column`: 司局 ID，可在 URL 找到


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
  - `moe.gov.cn/s78/:column/tongzhi`
  - `moe.gov.cn/s78/:column`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/gov/moe/s78/A13",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "moe/s78.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/gov/moe/s78.ts')",
  "name": "司局通知",
  "parameters": {
    "column": "司局 ID，可在 URL 找到"
  },
  "path": "/moe/s78/:column",
  "radar": [
    {
      "source": [
        "moe.gov.cn/s78/:column/tongzhi",
        "moe.gov.cn/s78/:column"
      ]
    }
  ]
}
```
