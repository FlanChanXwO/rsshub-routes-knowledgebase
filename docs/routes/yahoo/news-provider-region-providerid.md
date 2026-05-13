# Yahoo - 新聞來源

## Coverage
`index-only`

## Route
- Namespace: `yahoo`
- Namespace Name: `Yahoo`
- Route Path: `/news/provider/:region/:providerId`
- Route Name: `新聞來源`
- Example: `/yahoo/news/provider/tw/yahoo_tech_tw_942`
- URL: `hk.news.yahoo.com`
- Language: `zh-HK`
- Categories: `new-media`
- Maintainers: `TonyRL, williamgateszhao`
- Source Location: `news/provider.ts`
- Source Module: `() => import('@/routes/yahoo/news/provider.ts')`

## Description
`Region`

| 香港 | 台灣 |
| ---- | ---- |
| hk   | tw   |

`ProviderId`

除了可以通过路由"新聞來源列表"获得外, 也可通过 hk.news.yahoo.com/archive 和 tw.news.yahoo.com/archive 选择"新闻来源"后通过页面 Url 来获得。

例如 hk.news.yahoo.com/yahoo_movies_hk_660--所有分類/archive, `yahoo_movies_hk_660` 就是 ProviderId 。

## Parameters
- `region`: 地區, hk 或 tw, 分别表示香港雅虎和台湾雅虎
- `providerId`: 新聞來源 ID, 可透過路由"新聞來源列表"獲得


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
  "description": "\n`Region`\n\n| 香港 | 台灣 |\n| ---- | ---- |\n| hk   | tw   |\n\n`ProviderId`\n\n除了可以通过路由\"新聞來源列表\"获得外, 也可通过 hk.news.yahoo.com/archive 和 tw.news.yahoo.com/archive 选择\"新闻来源\"后通过页面 Url 来获得。\n\n例如 hk.news.yahoo.com/yahoo_movies_hk_660--所有分類/archive, `yahoo_movies_hk_660` 就是 ProviderId 。\n",
  "example": "/yahoo/news/provider/tw/yahoo_tech_tw_942",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news/provider.ts",
  "maintainers": [
    "TonyRL",
    "williamgateszhao"
  ],
  "module": "() => import('@/routes/yahoo/news/provider.ts')",
  "name": "新聞來源",
  "parameters": {
    "providerId": "新聞來源 ID, 可透過路由\"新聞來源列表\"獲得",
    "region": "地區, hk 或 tw, 分别表示香港雅虎和台湾雅虎"
  },
  "path": "/news/provider/:region/:providerId",
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
