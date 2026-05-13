# 新片场 - 发现

## Coverage
`index-only`

## Route
- Namespace: `xinpianchang`
- Namespace Name: `新片场`
- Route Path: `/discover/:params?`
- Route Name: `发现`
- Example: `/xinpianchang/discover`
- URL: `xinpianchang.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/xinpianchang/index.ts')`

## Description
::: tip
  跳转到欲订阅的分类页，将 URL 的 `/discover` 到末尾的部分填入 `params` 参数。

  如 [全部原创视频作品](https://www.xinpianchang.com/discover/article-0-0-all-all-0-0-score) 的 URL 为 `https://www.xinpianchang.com/discover/article-0-0-all-all-0-0-score`，其 `/discover` 到末尾的部分为 `article-0-0-all-all-0-0-score`，所以对应的路由为 [/xinpianchang/discover/article-0-0-all-all-0-0-score](https://rsshub.app/xinpianchang/discover/article-0-0-all-all-0-0-score)。
:::

## Parameters
- `params`: 参数，可在对应分类页 URL 中找到，默认为 `article-0-0-all-all-0-0-score` ，即全部


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
    "new-media"
  ],
  "description": "::: tip\n  跳转到欲订阅的分类页，将 URL 的 `/discover` 到末尾的部分填入 `params` 参数。\n\n  如 [全部原创视频作品](https://www.xinpianchang.com/discover/article-0-0-all-all-0-0-score) 的 URL 为 `https://www.xinpianchang.com/discover/article-0-0-all-all-0-0-score`，其 `/discover` 到末尾的部分为 `article-0-0-all-all-0-0-score`，所以对应的路由为 [/xinpianchang/discover/article-0-0-all-all-0-0-score](https://rsshub.app/xinpianchang/discover/article-0-0-all-all-0-0-score)。\n:::",
  "example": "/xinpianchang/discover",
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
  "module": "() => import('@/routes/xinpianchang/index.ts')",
  "name": "发现",
  "parameters": {
    "params": "参数，可在对应分类页 URL 中找到，默认为 `article-0-0-all-all-0-0-score` ，即全部"
  },
  "path": [
    "/discover/:params?",
    "/:params?"
  ]
}
```
