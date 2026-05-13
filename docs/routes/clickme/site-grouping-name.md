# ClickMe - 文章

## Coverage
`index-only`

## Route
- Namespace: `clickme`
- Namespace Name: `ClickMe`
- Route Path: `/:site/:grouping/:name`
- Route Name: `文章`
- Example: `/clickme/default/category/beauty`
- URL: `clickme.net`
- Language: `en`
- Categories: `other`
- Maintainers: `hoilc`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/clickme/index.ts')`

## Description
_None_

## Parameters
- `site`: 站点，`default`为普通站，`r18`为成人站，其它值默认为普通站
- `grouping`: 分组方式，`category`为分类，`tag`为标签，其他值默认为分类
- `name`: 分类名或标签名，分类名为英文，可以在分类 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/clickme/default/category/beauty",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "hoilc"
  ],
  "module": "() => import('@/routes/clickme/index.ts')",
  "name": "文章",
  "parameters": {
    "grouping": "分组方式，`category`为分类，`tag`为标签，其他值默认为分类",
    "name": "分类名或标签名，分类名为英文，可以在分类 URL 中找到",
    "site": "站点，`default`为普通站，`r18`为成人站，其它值默认为普通站"
  },
  "path": "/:site/:grouping/:name"
}
```
