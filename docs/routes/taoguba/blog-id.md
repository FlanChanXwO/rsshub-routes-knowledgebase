# 淘股吧 - 用户博客

## Coverage
`index-only`

## Route
- Namespace: `taoguba`
- Namespace Name: `淘股吧`
- Route Path: `/blog/:id`
- Route Name: `用户博客`
- Example: `/taoguba/blog/252069`
- URL: `tgb.cn`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `blog.ts`
- Source Module: `() => import('@/routes/taoguba/blog.ts')`

## Description
_None_

## Parameters
- `id`: 博客 id，可在对应博客页中找到


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
  - `tgb.cn/blog/:id`
  - `tgb.cn/`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/taoguba/blog/252069",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "blog.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/taoguba/blog.ts')",
  "name": "用户博客",
  "parameters": {
    "id": "博客 id，可在对应博客页中找到"
  },
  "path": "/blog/:id",
  "radar": [
    {
      "source": [
        "tgb.cn/blog/:id",
        "tgb.cn/"
      ]
    }
  ]
}
```
