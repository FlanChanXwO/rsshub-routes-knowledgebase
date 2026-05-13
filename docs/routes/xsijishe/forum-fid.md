# 司机社 - 论坛

## Coverage
`index-only`

## Route
- Namespace: `xsijishe`
- Namespace Name: `司机社`
- Route Path: `/forum/:fid`
- Route Name: `论坛`
- Example: `/xsijishe/forum/51`
- URL: `xsijishe.com`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `akynazh`
- Source Location: `forum.ts`
- Source Module: `() => import('@/routes/xsijishe/forum.ts')`

## Description
::: tip 关于子论坛 id 的获取方法
  `/xsijishe/forum/51` 对应于论坛 `https://xsijishe.com/forum-51-1.html`，这个论坛的 fid 为 51，也就是 `forum-{fid}-1` 中的 fid。
:::

## Parameters
- `fid`: 子论坛 id


## Features
- `requireConfig`: [{"description": "", "name": "XSIJISHE_COOKIE"}, {"description": "", "name": "XSIJISHE_USER_AGENT"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
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
    "bbs"
  ],
  "description": "::: tip 关于子论坛 id 的获取方法\n  `/xsijishe/forum/51` 对应于论坛 `https://xsijishe.com/forum-51-1.html`，这个论坛的 fid 为 51，也就是 `forum-{fid}-1` 中的 fid。\n:::",
  "example": "/xsijishe/forum/51",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": [
      {
        "description": "",
        "name": "XSIJISHE_COOKIE"
      },
      {
        "description": "",
        "name": "XSIJISHE_USER_AGENT"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "forum.ts",
  "maintainers": [
    "akynazh"
  ],
  "module": "() => import('@/routes/xsijishe/forum.ts')",
  "name": "论坛",
  "parameters": {
    "fid": "子论坛 id"
  },
  "path": "/forum/:fid"
}
```
