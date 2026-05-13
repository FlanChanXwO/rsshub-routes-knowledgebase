# 巴伦周刊中文版 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `barronschina`
- Namespace Name: `巴伦周刊中文版`
- Route Path: `/:id?`
- Route Name: `栏目`
- Example: `/barronschina`
- URL: `barronschina.com.cn/`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/barronschina/index.ts')`

## Description
::: tip
  栏目 id 留空则返回快讯，在对应页地址栏 `columnId=` 后可以看到。
:::

## Parameters
- `id`: 栏目 id，默认为快讯


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
  - `barronschina.com.cn/`
- `target`: `/:category?`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "::: tip\n  栏目 id 留空则返回快讯，在对应页地址栏 `columnId=` 后可以看到。\n:::",
  "example": "/barronschina",
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
    "nczitzk"
  ],
  "module": "() => import('@/routes/barronschina/index.ts')",
  "name": "栏目",
  "parameters": {
    "id": "栏目 id，默认为快讯"
  },
  "path": "/:id?",
  "radar": [
    {
      "source": [
        "barronschina.com.cn/"
      ],
      "target": "/:category?"
    }
  ],
  "url": "barronschina.com.cn/"
}
```
