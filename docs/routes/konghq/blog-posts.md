# Kong API 网关平台 - 博客最新文章

## Coverage
`index-only`

## Route
- Namespace: `konghq`
- Namespace Name: `Kong API 网关平台`
- Route Path: `/blog-posts`
- Route Name: `博客最新文章`
- Example: `/konghq/blog-posts`
- URL: `konghq.com/blog/*`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `piglei`
- Source Location: `blog-posts.ts`
- Source Module: `() => import('@/routes/konghq/blog-posts.ts')`

## Description
_None_

## Parameters
_None_


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
  - `konghq.com/blog/*`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/konghq/blog-posts",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "blog-posts.ts",
  "maintainers": [
    "piglei"
  ],
  "module": "() => import('@/routes/konghq/blog-posts.ts')",
  "name": "博客最新文章",
  "parameters": {},
  "path": "/blog-posts",
  "radar": [
    {
      "source": [
        "konghq.com/blog/*"
      ]
    }
  ],
  "url": "konghq.com/blog/*"
}
```
