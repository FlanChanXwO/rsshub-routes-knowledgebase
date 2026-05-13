# 财新博客 - 用户博客

## Coverage
`index-only`

## Route
- Namespace: `caixin`
- Namespace Name: `财新博客`
- Route Path: `/blog/:column?`
- Route Name: `用户博客`
- Example: `/caixin/blog/zhangwuchang`
- URL: `caixin.com`
- Language: `zh-CN`
- Categories: `blog`
- Maintainers: `None`
- Source Location: `blog.ts`
- Source Module: `() => import('@/routes/caixin/blog.ts')`

## Description
通过提取文章全文，以提供比官方源更佳的阅读体验.

## Parameters
- `column`: 博客名称，可在博客主页的 URL 找到


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
  "description": "通过提取文章全文，以提供比官方源更佳的阅读体验.",
  "example": "/caixin/blog/zhangwuchang",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "blog.ts",
  "maintainers": [],
  "module": "() => import('@/routes/caixin/blog.ts')",
  "name": "用户博客",
  "parameters": {
    "column": "博客名称，可在博客主页的 URL 找到"
  },
  "path": "/blog/:column?"
}
```
