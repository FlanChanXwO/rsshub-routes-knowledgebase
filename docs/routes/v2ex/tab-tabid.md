# V2EX - 标签

## Coverage
`index-only`

## Route
- Namespace: `v2ex`
- Namespace Name: `V2EX`
- Route Path: `/tab/:tabid`
- Route Name: `标签`
- Example: `/v2ex/tab/hot`
- URL: `v2ex.com`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `liyefox`
- Source Location: `tab.ts`
- Source Module: `() => import('@/routes/v2ex/tab.ts')`

## Description
_None_

## Parameters
- `tabid`: tab标签ID,在 URL 可以找到


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
    "bbs"
  ],
  "example": "/v2ex/tab/hot",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "tab.ts",
  "maintainers": [
    "liyefox"
  ],
  "module": "() => import('@/routes/v2ex/tab.ts')",
  "name": "标签",
  "parameters": {
    "tabid": "tab标签ID,在 URL 可以找到"
  },
  "path": "/tab/:tabid",
  "view": 0
}
```
