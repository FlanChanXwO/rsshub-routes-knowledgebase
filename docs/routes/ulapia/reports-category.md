# 乌拉邦 - 频道

## Coverage
`index-only`

## Route
- Namespace: `ulapia`
- Namespace Name: `乌拉邦`
- Route Path: `/reports/:category?`
- Route Name: `频道`
- Example: `/ulapia/reports/stock_research`
- URL: `www.ulapia.com`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `Fatpandac`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/ulapia/index.ts')`

## Description
|     个股研报    |      行业研报      |      策略研报      |     宏观研报    |    新股研报   | 券商晨报（今日晨报） |
| :-------------: | :----------------: | :----------------: | :-------------: | :-----------: | :------------------: |
| stock_research | industry_research | strategy_research | macro_research | ipo_research |    brokerage_news   |

## Parameters
- `category`: 频道类型，默认为券商晨报（今日晨报）


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
    "finance"
  ],
  "description": "|     个股研报    |      行业研报      |      策略研报      |     宏观研报    |    新股研报   | 券商晨报（今日晨报） |\n| :-------------: | :----------------: | :----------------: | :-------------: | :-----------: | :------------------: |\n| stock_research | industry_research | strategy_research | macro_research | ipo_research |    brokerage_news   |",
  "example": "/ulapia/reports/stock_research",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "module": "() => import('@/routes/ulapia/index.ts')",
  "name": "频道",
  "parameters": {
    "category": "频道类型，默认为券商晨报（今日晨报）"
  },
  "path": "/reports/:category?"
}
```
