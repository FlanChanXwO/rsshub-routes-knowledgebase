# 国家能源局 - 投诉建议

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/safe/complaint/:site?`
- Route Name: `投诉建议`
- Example: `/gov/safe/complaint/beijing`
- URL: `www.nea.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `safe/complaint.ts`
- Source Module: `() => import('@/routes/gov/safe/complaint.ts')`

## Description
_None_

## Parameters
- `site`: 站点，见上表，默认为 beijing


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
    "government"
  ],
  "example": "/gov/safe/complaint/beijing",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "safe/complaint.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/gov/safe/complaint.ts')",
  "name": "投诉建议",
  "parameters": {
    "site": "站点，见上表，默认为 beijing"
  },
  "path": "/safe/complaint/:site?"
}
```
