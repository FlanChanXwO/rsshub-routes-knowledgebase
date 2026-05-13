# 地震速报 - 中国地震局

## Coverage
`index-only`

## Route
- Namespace: `earthquake`
- Namespace Name: `地震速报`
- Route Path: `/:region?`
- Route Name: `中国地震局`
- Example: `/earthquake`
- URL: `www.cea.gov.cn/cea/xwzx/zqsd/index.html`
- Language: `zh-CN`
- Categories: `forecast`
- Maintainers: `LogicJake`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/earthquake/index.ts')`

## Description
可通过全局过滤参数订阅您感兴趣的地区.

## Parameters
- `region`: 区域，0全部，1国内（默认），2国外


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.cea.gov.cn/cea/xwzx/zqsd/index.html`
  - `www.cea.gov.cn/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "description": "可通过全局过滤参数订阅您感兴趣的地区.",
  "example": "/earthquake",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "LogicJake"
  ],
  "module": "() => import('@/routes/earthquake/index.ts')",
  "name": "中国地震局",
  "parameters": {
    "region": "区域，0全部，1国内（默认），2国外"
  },
  "path": "/:region?",
  "radar": [
    {
      "source": [
        "www.cea.gov.cn/cea/xwzx/zqsd/index.html",
        "www.cea.gov.cn/"
      ],
      "target": ""
    }
  ],
  "url": "www.cea.gov.cn/cea/xwzx/zqsd/index.html"
}
```
