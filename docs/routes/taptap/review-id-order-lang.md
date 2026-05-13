# TapTap - 游戏评价

## Coverage
`index-only`

## Route
- Namespace: `taptap`
- Namespace Name: `TapTap`
- Route Path: `/review/:id/:order?/:lang?`
- Route Name: `游戏评价`
- Example: `/taptap/review/142793/hot`
- URL: `www.taptap.io`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `hoilc, TonyRL`
- Source Location: `review-cn.ts`
- Source Module: `() => import('@/routes/taptap/review-cn.ts')`

## Description
| 最新   | 综合 |
| --- | --- |
| new | hot |

## Parameters
- `id`: 游戏 ID，游戏主页 URL 中获取
- `order`: 排序方式，空为综合，可选如下
- `lang`: 语言，`zh-CN` 或 `zh-TW`，默认为 `zh-CN`


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
  - `www.taptap.cn/app/:id/review`
  - `www.taptap.cn/app/:id`
- `target`: `/review/:id`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| 最新   | 综合 |\n| --- | --- |\n| new | hot |",
  "example": "/taptap/review/142793/hot",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "review-cn.ts",
  "maintainers": [
    "hoilc",
    "TonyRL"
  ],
  "module": "() => import('@/routes/taptap/review-cn.ts')",
  "name": "游戏评价",
  "parameters": {
    "id": "游戏 ID，游戏主页 URL 中获取",
    "lang": "语言，`zh-CN` 或 `zh-TW`，默认为 `zh-CN`",
    "order": "排序方式，空为综合，可选如下"
  },
  "path": "/review/:id/:order?/:lang?",
  "radar": [
    {
      "source": [
        "www.taptap.cn/app/:id/review",
        "www.taptap.cn/app/:id"
      ],
      "target": "/review/:id"
    }
  ]
}
```
