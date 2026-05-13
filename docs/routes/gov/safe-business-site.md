# 国家能源局 - 业务咨询

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/safe/business/:site?`
- Route Name: `业务咨询`
- Example: `/gov/safe/business/beijing`
- URL: `www.nea.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `safe/business.ts`
- Source Module: `() => import('@/routes/gov/safe/business.ts')`

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
  "example": "/gov/safe/business/beijing",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "safe/business.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/gov/safe/business.ts')",
  "name": "业务咨询",
  "parameters": {
    "site": "站点，见上表，默认为 beijing"
  },
  "path": "/safe/business/:site?"
}
```
