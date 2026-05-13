# AcFun - 番剧

## Coverage
`index-only`

## Route
- Namespace: `acfun`
- Namespace Name: `AcFun`
- Route Path: `/bangumi/:id/:embed?`
- Route Name: `番剧`
- Example: `/acfun/bangumi/6000617`
- URL: `www.acfun.cn`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `xyqfer`
- Source Location: `bangumi.ts`
- Source Module: `() => import('@/routes/acfun/bangumi.ts')`

## Description
::: tip
番剧 id 不包含开头的 aa。
例如：`https://www.acfun.cn/bangumi/aa6000617` 的番剧 id 是 6000617，不包括开头的 aa。
:::

## Parameters
- `id`: 番剧 id
- `embed`: 默认为开启内嵌视频, 任意值为关闭


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
    "anime"
  ],
  "description": "::: tip\n番剧 id 不包含开头的 aa。\n例如：`https://www.acfun.cn/bangumi/aa6000617` 的番剧 id 是 6000617，不包括开头的 aa。\n:::",
  "example": "/acfun/bangumi/6000617",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "bangumi.ts",
  "maintainers": [
    "xyqfer"
  ],
  "module": "() => import('@/routes/acfun/bangumi.ts')",
  "name": "番剧",
  "parameters": {
    "embed": "默认为开启内嵌视频, 任意值为关闭",
    "id": "番剧 id"
  },
  "path": "/bangumi/:id/:embed?",
  "view": 3
}
```
