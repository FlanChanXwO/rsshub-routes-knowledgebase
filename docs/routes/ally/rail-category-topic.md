# 艾莱资讯 - 世界轨道交通资讯网

## Coverage
`index-only`

## Route
- Namespace: `ally`
- Namespace Name: `艾莱资讯`
- Route Path: `/rail/:category?/:topic?`
- Route Name: `世界轨道交通资讯网`
- Example: `/ally/rail/hyzix/chengguijiaotong`
- URL: `rail.ally.net.cn/`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `Rongronggg9`
- Source Location: `rail.ts`
- Source Module: `() => import('@/routes/ally/rail.ts')`

## Description
::: tip
  默认抓取前 20 条，可通过 `?limit=` 改变。
:::

## Parameters
- `category`: 分类，可在 URL 中找到；略去则抓取首页
- `topic`: 话题，可在 URL 中找到；并非所有页面均有此字段


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
  - `rail.ally.net.cn/`
  - `rail.ally.net.cn/html/:category?/:topic?`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n  默认抓取前 20 条，可通过 `?limit=` 改变。\n:::",
  "example": "/ally/rail/hyzix/chengguijiaotong",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "rail.ts",
  "maintainers": [
    "Rongronggg9"
  ],
  "module": "() => import('@/routes/ally/rail.ts')",
  "name": "世界轨道交通资讯网",
  "parameters": {
    "category": "分类，可在 URL 中找到；略去则抓取首页",
    "topic": "话题，可在 URL 中找到；并非所有页面均有此字段"
  },
  "path": "/rail/:category?/:topic?",
  "radar": [
    {
      "source": [
        "rail.ally.net.cn/",
        "rail.ally.net.cn/html/:category?/:topic?"
      ]
    }
  ],
  "url": "rail.ally.net.cn/"
}
```
