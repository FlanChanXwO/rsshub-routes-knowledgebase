# 少数派 sspai - 用户收藏

## Coverage
`index-only`

## Route
- Namespace: `sspai`
- Namespace Name: `少数派 sspai`
- Route Path: `/bookmarks/:slug`
- Route Name: `用户收藏`
- Example: `/sspai/bookmarks/urfp0d9i`
- URL: `sspai.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `curly210102`
- Source Location: `bookmarks.ts`
- Source Module: `() => import('@/routes/sspai/bookmarks.ts')`

## Description
_None_

## Parameters
- `slug`: 用户 slug，可在个人主页URL中找到


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
  - `sspai.com/u/:slug/bookmark_posts`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/sspai/bookmarks/urfp0d9i",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "bookmarks.ts",
  "maintainers": [
    "curly210102"
  ],
  "module": "() => import('@/routes/sspai/bookmarks.ts')",
  "name": "用户收藏",
  "parameters": {
    "slug": "用户 slug，可在个人主页URL中找到"
  },
  "path": "/bookmarks/:slug",
  "radar": [
    {
      "source": [
        "sspai.com/u/:slug/bookmark_posts"
      ]
    }
  ]
}
```
