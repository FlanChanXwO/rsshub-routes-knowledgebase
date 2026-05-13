# 澳门卫生局 - 最新消息

## Coverage
`index-only`

## Route
- Namespace: `ssm`
- Namespace Name: `澳门卫生局`
- Route Path: `/news`
- Route Name: `最新消息`
- Example: `/ssm/news`
- URL: `www.ssm.gov.mo/`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `Fatpandac`
- Source Location: `news.tsx`
- Source Module: `() => import('@/routes/ssm/news.tsx')`

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
  - `www.ssm.gov.mo/`
  - `www.ssm.gov.mo/portal`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/ssm/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.tsx",
  "maintainers": [
    "Fatpandac"
  ],
  "module": "() => import('@/routes/ssm/news.tsx')",
  "name": "最新消息",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "www.ssm.gov.mo/",
        "www.ssm.gov.mo/portal"
      ]
    }
  ],
  "url": "www.ssm.gov.mo/"
}
```
