# 雪球 - 股票信息

## Coverage
`index-only`

## Route
- Namespace: `xueqiu`
- Namespace Name: `雪球`
- Route Path: `/xueqiu/stock_info/:id/:type?`
- Route Name: `股票信息`
- Example: `/xueqiu/stock_info/SZ000002`
- URL: `danjuanapp.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `YuYang`
- Source Location: `stock-info.ts`
- Source Module: `_None_`

## Description
| 公告         | 新闻 | 研报     |
| ------------ | ---- | -------- |
| announcement | news | research |

## Parameters
- `id`: 股票代码（需要带上交易所）
- `type`: 动态的类型, 不填则为股票公告


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
  - `xueqiu.com/S/:id`
  - `xueqiu.com/s/:id`
- `target`: `/stock_info/:id`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| 公告         | 新闻 | 研报     |\n| ------------ | ---- | -------- |\n| announcement | news | research |",
  "example": "/xueqiu/stock_info/SZ000002",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 28,
  "location": "stock-info.ts",
  "maintainers": [
    "YuYang"
  ],
  "name": "股票信息",
  "parameters": {
    "id": "股票代码（需要带上交易所）",
    "type": "动态的类型, 不填则为股票公告"
  },
  "path": "/stock_info/:id/:type?",
  "radar": [
    {
      "source": [
        "xueqiu.com/S/:id",
        "xueqiu.com/s/:id"
      ],
      "target": "/stock_info/:id"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "兆易创新 - 自选股新闻 - Powered by RSSHub",
      "errorAt": "2024-11-22T14:04:03.723Z",
      "errorMessage": "Cannot read properties of undefined (reading 'map')\n",
      "id": "64923928046286858",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xueqiu.com/S/SH603986",
      "title": "SH603986 兆易创新 - 自选股新闻",
      "type": "feed",
      "url": "rsshub://xueqiu/stock_info/SH603986/news"
    },
    {
      "description": "- 公告 - Powered by RSSHub",
      "errorAt": "2024-11-22T14:04:44.329Z",
      "errorMessage": "Cannot read properties of undefined (reading 'map')\n",
      "id": "64923928046286863",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xueqiu.com/S/SH603501",
      "title": "SH603501 - 公告",
      "type": "feed",
      "url": "rsshub://xueqiu/stock_info/SH603501"
    }
  ]
}
```
