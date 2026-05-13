# 上海证券交易所 - 监管问询

## Coverage
`index-only`

## Route
- Namespace: `sse`
- Namespace Name: `上海证券交易所`
- Route Path: `/inquire`
- Route Name: `监管问询`
- Example: `/sse/inquire`
- URL: `www.sse.com.cn/disclosure/credibility/supervision/inquiries`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `Jeason0228`
- Source Location: `inquire.tsx`
- Source Module: `() => import('@/routes/sse/inquire.tsx')`

## Description
_None_

## Parameters
_None_


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
  - `www.sse.com.cn/disclosure/credibility/supervision/inquiries`
  - `www.sse.com.cn/`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/sse/inquire",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "inquire.tsx",
  "maintainers": [
    "Jeason0228"
  ],
  "module": "() => import('@/routes/sse/inquire.tsx')",
  "name": "监管问询",
  "parameters": {},
  "path": "/inquire",
  "radar": [
    {
      "source": [
        "www.sse.com.cn/disclosure/credibility/supervision/inquiries",
        "www.sse.com.cn/"
      ]
    }
  ],
  "url": "www.sse.com.cn/disclosure/credibility/supervision/inquiries"
}
```
