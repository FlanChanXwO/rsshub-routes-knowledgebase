# 竹白 - 文章

## Coverage
`index-only`

## Route
- Namespace: `zhubai`
- Namespace Name: `竹白`
- Route Path: `/posts/:id`
- Route Name: `文章`
- Example: `/zhubai/posts/via`
- URL: `zhubai.love`
- Language: `zh-CN`
- Categories: `blog`
- Maintainers: `naixy28`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/zhubai/index.ts')`

## Description
::: tip
  在路由末尾处加上 `?limit=限制获取数目` 来限制获取条目数量，默认值为`20`
:::

## Parameters
- `id`: `id` 为竹白主页 url 中的三级域名，如 via.zhubai.love 的 `id` 为 `via`


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
    "blog"
  ],
  "description": "::: tip\n  在路由末尾处加上 `?limit=限制获取数目` 来限制获取条目数量，默认值为`20`\n:::",
  "example": "/zhubai/posts/via",
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
    "naixy28"
  ],
  "module": "() => import('@/routes/zhubai/index.ts')",
  "name": "文章",
  "parameters": {
    "id": "`id` 为竹白主页 url 中的三级域名，如 via.zhubai.love 的 `id` 为 `via`"
  },
  "path": "/posts/:id"
}
```
