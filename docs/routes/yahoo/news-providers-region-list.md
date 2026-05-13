# Yahoo - 新聞來源列表

## Coverage
`index-only`

## Route
- Namespace: `yahoo`
- Namespace Name: `Yahoo`
- Route Path: `/news/providers/:region/list`
- Route Name: `新聞來源列表`
- Example: `/yahoo/news/providers/tw/list`
- URL: `hk.news.yahoo.com`
- Language: `zh-HK`
- Categories: `new-media`
- Maintainers: `TonyRL, williamgateszhao`
- Source Location: `news/provider-helper.ts`
- Source Module: `() => import('@/routes/yahoo/news/provider-helper.ts')`

## Description
_None_

## Parameters
- `region`: 地区, 同路由"新闻来源"中的支持地区, 即 hk 或 tw


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
  - `hk.news.yahoo.com/`
### Rule 2
- `source`:
  - `tw.news.yahoo.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/yahoo/news/providers/tw/list",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news/provider-helper.ts",
  "maintainers": [
    "TonyRL",
    "williamgateszhao"
  ],
  "module": "() => import('@/routes/yahoo/news/provider-helper.ts')",
  "name": "新聞來源列表",
  "parameters": {
    "region": "地区, 同路由\"新闻来源\"中的支持地区, 即 hk 或 tw"
  },
  "path": "/news/providers/:region/list",
  "radar": [
    {
      "source": [
        "hk.news.yahoo.com/"
      ]
    },
    {
      "source": [
        "tw.news.yahoo.com/"
      ]
    }
  ]
}
```
