# 雪球 - 股票信息

## Coverage
`index-only`

## Route
- Namespace: `xueqiu`
- Namespace Name: `雪球`
- Route Path: `/stock_info/:id/:type?`
- Route Name: `股票信息`
- Example: `/xueqiu/stock_info/SZ000002`
- URL: `danjuanapp.com`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `YuYang`
- Source Location: `stock-info.ts`
- Source Module: `() => import('@/routes/xueqiu/stock-info.ts')`

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
  "location": "stock-info.ts",
  "maintainers": [
    "YuYang"
  ],
  "module": "() => import('@/routes/xueqiu/stock-info.ts')",
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
  ]
}
```
