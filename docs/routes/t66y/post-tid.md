# 草榴社区 - 帖子跟踪

## Coverage
`index-only`

## Route
- Namespace: `t66y`
- Namespace Name: `草榴社区`
- Route Path: `/post/:tid`
- Route Name: `帖子跟踪`
- Example: `/t66y/post/3286088`
- URL: `t66y.com`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `cnzgray`
- Source Location: `post.ts`
- Source Module: `() => import('@/routes/t66y/post.ts')`

## Description
::: tip
  帖子 id 查找办法:

  打开想跟踪的帖子，比如：`https://t66y.com/htm_data/20/1811/3286088.html` 其中 `3286088` 就是帖子 id。
:::

## Parameters
- `tid`: 帖子 id, 可在帖子 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "::: tip\n  帖子 id 查找办法:\n\n  打开想跟踪的帖子，比如：`https://t66y.com/htm_data/20/1811/3286088.html` 其中 `3286088` 就是帖子 id。\n:::",
  "example": "/t66y/post/3286088",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "post.ts",
  "maintainers": [
    "cnzgray"
  ],
  "module": "() => import('@/routes/t66y/post.ts')",
  "name": "帖子跟踪",
  "parameters": {
    "tid": "帖子 id, 可在帖子 URL 中找到"
  },
  "path": "/post/:tid"
}
```
