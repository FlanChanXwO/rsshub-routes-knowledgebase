# 百度 - 精品帖子

## Coverage
`index-only`

## Route
- Namespace: `baidu`
- Namespace Name: `百度`
- Route Path: `/tieba/forum/good/:kw/:cid?/:sortBy?`
- Route Name: `精品帖子`
- Example: `/baidu/tieba/forum/good/女图`
- URL: `www.baidu.com`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `u3u`
- Source Location: `tieba/forum.tsx`
- Source Module: `() => import('@/routes/baidu/tieba/forum.tsx')`

## Description
_None_

## Parameters
- `kw`: 吧名
- `cid`: 精品分类，默认为 `0`（全部分类），如果不传 `cid` 则获取全部分类
- `sortBy`: 排序方式：`created`, `replied`。默认为 `created`


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
    "bbs"
  ],
  "example": "/baidu/tieba/forum/good/女图",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "tieba/forum.tsx",
  "maintainers": [
    "u3u"
  ],
  "module": "() => import('@/routes/baidu/tieba/forum.tsx')",
  "name": "精品帖子",
  "parameters": {
    "cid": "精品分类，默认为 `0`（全部分类），如果不传 `cid` 则获取全部分类",
    "kw": "吧名",
    "sortBy": "排序方式：`created`, `replied`。默认为 `created`"
  },
  "path": [
    "/tieba/forum/good/:kw/:cid?/:sortBy?",
    "/tieba/forum/:kw/:sortBy?"
  ]
}
```
