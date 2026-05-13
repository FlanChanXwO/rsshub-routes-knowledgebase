# 趣集 - 盐选故事搜索

## Coverage
`index-only`

## Route
- Namespace: `ifun`
- Namespace Name: `趣集`
- Route Path: `/n/search/:keywords`
- Route Name: `盐选故事搜索`
- Example: `/ifun/n/search/NPC`
- URL: `n.ifun.cool`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `n/search.ts`
- Source Module: `() => import('@/routes/ifun/n/search.ts')`

## Description
::: tip
若订阅 [关键词：NPC](https://n.ifun.cool/search-result/?s=NPC)，网址为 `https://n.ifun.cool/search-result/?s=NPC`，请截取 `s` 的值 `NPC` 作为 `keywords` 参数填入，此时目标路由为 [`/ifun/n/search/NPC`](https://rsshub.app/ifun/n/search/NPC)。
:::

## Parameters
- `keywords`: 搜索关键字


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `n.ifun.cool/search-result`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n若订阅 [关键词：NPC](https://n.ifun.cool/search-result/?s=NPC)，网址为 `https://n.ifun.cool/search-result/?s=NPC`，请截取 `s` 的值 `NPC` 作为 `keywords` 参数填入，此时目标路由为 [`/ifun/n/search/NPC`](https://rsshub.app/ifun/n/search/NPC)。\n:::\n    ",
  "example": "/ifun/n/search/NPC",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "n/search.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/ifun/n/search.ts')",
  "name": "盐选故事搜索",
  "parameters": {
    "keywords": "搜索关键字"
  },
  "path": "/n/search/:keywords",
  "radar": [
    {
      "source": [
        "n.ifun.cool/search-result"
      ]
    }
  ],
  "url": "n.ifun.cool",
  "view": 0
}
```
