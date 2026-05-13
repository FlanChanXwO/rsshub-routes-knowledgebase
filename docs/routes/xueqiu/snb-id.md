# 雪球 - 组合最新调仓信息

## Coverage
`index-only`

## Route
- Namespace: `xueqiu`
- Namespace Name: `雪球`
- Route Path: `/snb/:id`
- Route Name: `组合最新调仓信息`
- Example: `/xueqiu/snb/ZH1288184`
- URL: `danjuanapp.com`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `ZhishanZhang`
- Source Location: `snb.ts`
- Source Module: `() => import('@/routes/xueqiu/snb.ts')`

## Description
_None_

## Parameters
- `id`: 组合代码, 可在组合主页 URL 中找到.


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
  - `xueqiu.com/P/:id`
  - `xueqiu.com/p/:id`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/xueqiu/snb/ZH1288184",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "snb.ts",
  "maintainers": [
    "ZhishanZhang"
  ],
  "module": "() => import('@/routes/xueqiu/snb.ts')",
  "name": "组合最新调仓信息",
  "parameters": {
    "id": "组合代码, 可在组合主页 URL 中找到."
  },
  "path": "/snb/:id",
  "radar": [
    {
      "source": [
        "xueqiu.com/P/:id",
        "xueqiu.com/p/:id"
      ]
    }
  ]
}
```
