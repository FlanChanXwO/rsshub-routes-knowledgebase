# NGA - 帖子

## Coverage
`index-only`

## Route
- Namespace: `nga`
- Namespace Name: `NGA`
- Route Path: `/post/:tid/:authorId?`
- Route Name: `帖子`
- Example: `/nga/post/18449558`
- URL: `bbs.nga.cn`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `xyqfer, syrinka`
- Source Location: `post.ts`
- Source Module: `() => import('@/routes/nga/post.ts')`

## Description
_None_

## Parameters
- `tid`: 帖子 id, 可在帖子 URL 找到
- `authorId`: 作者 id


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
  "example": "/nga/post/18449558",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "post.ts",
  "maintainers": [
    "xyqfer",
    "syrinka"
  ],
  "module": "() => import('@/routes/nga/post.ts')",
  "name": "帖子",
  "parameters": {
    "authorId": "作者 id",
    "tid": "帖子 id, 可在帖子 URL 找到"
  },
  "path": "/post/:tid/:authorId?"
}
```
