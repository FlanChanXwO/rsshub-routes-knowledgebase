# 百度 - 用户帖子

## Coverage
`index-only`

## Route
- Namespace: `baidu`
- Namespace Name: `百度`
- Route Path: `/tieba/user/:uid`
- Route Name: `用户帖子`
- Example: `/baidu/tieba/user/斗鱼游戏君`
- URL: `www.baidu.com`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `igxlin, nczitzk`
- Source Location: `tieba/user.ts`
- Source Module: `() => import('@/routes/baidu/tieba/user.ts')`

## Description
用户 ID 可以通过打开用户的主页后查看地址栏的 `un` 字段来获取。

## Parameters
- `uid`: 用户 ID


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
  "description": "用户 ID 可以通过打开用户的主页后查看地址栏的 `un` 字段来获取。",
  "example": "/baidu/tieba/user/斗鱼游戏君",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "tieba/user.ts",
  "maintainers": [
    "igxlin",
    "nczitzk"
  ],
  "module": "() => import('@/routes/baidu/tieba/user.ts')",
  "name": "用户帖子",
  "parameters": {
    "uid": "用户 ID"
  },
  "path": "/tieba/user/:uid"
}
```
