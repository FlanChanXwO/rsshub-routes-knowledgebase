# 12306 - 最新动态

## Coverage
`index-only`

## Route
- Namespace: `12306`
- Namespace Name: `12306`
- Route Path: `/zxdt/:id?`
- Route Name: `最新动态`
- Example: `/12306/zxdt`
- URL: `www.12306.cn/`
- Language: `zh-CN`
- Categories: `travel`
- Maintainers: `LogicJake`
- Source Location: `zxdt.ts`
- Source Module: `() => import('@/routes/12306/zxdt.ts')`

## Description
_None_

## Parameters
- `id`: 铁路局id，可在 URL 中找到，不填默认显示所有铁路局动态


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
  - `www.12306.cn/`
  - `www.12306.cn/mormhweb/1/:id/index_fl.html`
- `target`: `/zxdt/:id`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/12306/zxdt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "zxdt.ts",
  "maintainers": [
    "LogicJake"
  ],
  "module": "() => import('@/routes/12306/zxdt.ts')",
  "name": "最新动态",
  "parameters": {
    "id": "铁路局id，可在 URL 中找到，不填默认显示所有铁路局动态"
  },
  "path": "/zxdt/:id?",
  "radar": [
    {
      "source": [
        "www.12306.cn/",
        "www.12306.cn/mormhweb/1/:id/index_fl.html"
      ],
      "target": "/zxdt/:id"
    }
  ],
  "url": "www.12306.cn/"
}
```
