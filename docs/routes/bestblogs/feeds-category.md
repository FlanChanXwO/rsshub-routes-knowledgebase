# bestblogs.dev - 文章列表

## Coverage
`index-only`

## Route
- Namespace: `bestblogs`
- Namespace Name: `bestblogs.dev`
- Route Path: `/feeds/:category?`
- Route Name: `文章列表`
- Example: `/bestblogs/feeds/featured`
- URL: `www.bestblogs.dev`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `zhenlohuang`
- Source Location: `feeds.ts`
- Source Module: `() => import('@/routes/bestblogs/feeds.ts')`

## Description
_None_

## Parameters
- `category`: the category of articles. Can be `programming`, `ai`, `product`, `business` or `featured`. Default is `featured`


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
    "programming"
  ],
  "example": "/bestblogs/feeds/featured",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "feeds.ts",
  "maintainers": [
    "zhenlohuang"
  ],
  "module": "() => import('@/routes/bestblogs/feeds.ts')",
  "name": "文章列表",
  "parameters": {
    "category": "the category of articles. Can be `programming`, `ai`, `product`, `business` or `featured`. Default is `featured`"
  },
  "path": "/feeds/:category?"
}
```
