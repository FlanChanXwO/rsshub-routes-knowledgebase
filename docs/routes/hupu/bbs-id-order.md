# 虎扑 - 社区

## Coverage
`index-only`

## Route
- Namespace: `hupu`
- Namespace Name: `虎扑`
- Route Path: `/bbs/:id?/:order?`
- Route Name: `社区`
- Example: `/hupu/bbs/topic-daily`
- URL: `.hupu.com`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `LogicJake, nczitzk`
- Source Location: `bbs.tsx`
- Source Module: `() => import('@/routes/hupu/bbs.tsx')`

## Description
::: tip
  更多社区参见 [社区](https://bbs.hupu.com)
:::

## Parameters
- `id`: 编号，可在对应社区 URL 中找到，默认为#步行街主干道
- `order`: 排序方式，可选 `0` 即 最新回复 或 `1` 即 最新发布，默认为最新回复


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
  - `m.hupu.com/:category`
  - `m.hupu.com/`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "::: tip\n  更多社区参见 [社区](https://bbs.hupu.com)\n:::",
  "example": "/hupu/bbs/topic-daily",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "bbs.tsx",
  "maintainers": [
    "LogicJake",
    "nczitzk"
  ],
  "module": "() => import('@/routes/hupu/bbs.tsx')",
  "name": "社区",
  "parameters": {
    "id": "编号，可在对应社区 URL 中找到，默认为#步行街主干道",
    "order": "排序方式，可选 `0` 即 最新回复 或 `1` 即 最新发布，默认为最新回复"
  },
  "path": [
    "/bbs/:id?/:order?",
    "/bxj/:id?/:order?"
  ],
  "radar": [
    {
      "source": [
        "m.hupu.com/:category",
        "m.hupu.com/"
      ],
      "target": "/:category"
    }
  ]
}
```
