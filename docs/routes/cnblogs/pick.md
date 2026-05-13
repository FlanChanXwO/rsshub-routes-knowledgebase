# 博客园 - 10 天推荐排行榜

## Coverage
`index-only`

## Route
- Namespace: `cnblogs`
- Namespace Name: `博客园`
- Route Path: `/pick`
- Route Name: `10 天推荐排行榜`
- Example: `/cnblogs/aggsite/topdiggs`
- URL: `www.cnblogs.com/pick`
- Language: `zh-CN`
- Categories: `blog`
- Maintainers: `hujingnb`
- Source Location: `common.ts`
- Source Module: `() => import('@/routes/cnblogs/common.ts')`

## Description
在博客园主页的分类出可查看所有类型。例如，go 的分类地址为: `https://www.cnblogs.com/cate/go/`, 则: [`/cnblogs/cate/go`](https://rsshub.app/cnblogs/cate/go)

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
  - `www.cnblogs.com/aggsite/topdiggs`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "description": "在博客园主页的分类出可查看所有类型。例如，go 的分类地址为: `https://www.cnblogs.com/cate/go/`, 则: [`/cnblogs/cate/go`](https://rsshub.app/cnblogs/cate/go)",
  "example": "/cnblogs/aggsite/topdiggs",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "common.ts",
  "maintainers": [
    "hujingnb"
  ],
  "module": "() => import('@/routes/cnblogs/common.ts')",
  "name": "10 天推荐排行榜",
  "parameters": {},
  "path": [
    "/aggsite/topdiggs",
    "/aggsite/topviews",
    "/aggsite/headline",
    "/cate/:type",
    "/pick"
  ],
  "radar": [
    {
      "source": [
        "www.cnblogs.com/aggsite/topdiggs"
      ]
    }
  ],
  "url": "www.cnblogs.com/pick"
}
```
