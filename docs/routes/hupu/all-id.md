# 虎扑 - 热帖

## Coverage
`index-only`

## Route
- Namespace: `hupu`
- Namespace Name: `虎扑`
- Route Path: `/all/:id?`
- Route Name: `热帖`
- Example: `/hupu/all/topic-daily`
- URL: `.hupu.com`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `nczitzk`
- Source Location: `all.tsx`
- Source Module: `() => import('@/routes/hupu/all.tsx')`

## Description
::: tip
  更多热帖版面参见 [论坛](https://bbs.hupu.com)
:::

## Parameters
- `id`: 编号，可在对应热帖版面 URL 中找到，默认为步行街每日话题


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
  "description": "::: tip\n  更多热帖版面参见 [论坛](https://bbs.hupu.com)\n:::",
  "example": "/hupu/all/topic-daily",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "all.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/hupu/all.tsx')",
  "name": "热帖",
  "parameters": {
    "id": "编号，可在对应热帖版面 URL 中找到，默认为步行街每日话题"
  },
  "path": "/all/:id?",
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
