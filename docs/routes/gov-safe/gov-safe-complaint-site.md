# 国家外汇管理局 - 投诉建议

## Coverage
`index-only`

## Route
- Namespace: `gov/safe`
- Namespace Name: `国家外汇管理局`
- Route Path: `/gov/safe/complaint/:site?`
- Route Name: `投诉建议`
- Example: `/gov/safe/complaint/beijing`
- URL: `www.safe.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `complaint.ts`
- Source Module: `_None_`

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
  "heat": 0,
  "location": "complaint.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "投诉建议",
  "parameters": {
    "site": "站点，见上表，默认为 beijing"
  },
  "path": "/complaint/:site?",
  "topFeeds": []
}
```
