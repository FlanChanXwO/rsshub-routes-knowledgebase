# 百度 - 用户帖子

## Coverage
`index-only`

## Route
- Namespace: `baidu`
- Namespace Name: `百度`
- Route Path: `/baidu/tieba/user/:uid`
- Route Name: `用户帖子`
- Example: `/baidu/tieba/user/斗鱼游戏君`
- URL: `www.baidu.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `igxlin, nczitzk`
- Source Location: `tieba/user.ts`
- Source Module: `_None_`

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
  "heat": 12,
  "location": "tieba/user.ts",
  "maintainers": [
    "igxlin",
    "nczitzk"
  ],
  "name": "用户帖子",
  "parameters": {
    "uid": "用户 ID"
  },
  "path": "/tieba/user/:uid",
  "topFeeds": [
    {
      "description": "狼獾赝月 的贴吧 - Powered by RSSHub",
      "errorAt": "2025-11-02T19:26:02.118Z",
      "errorMessage": "[GET] \"https://tieba.baidu.com/home/main?un=狼獾赝月\": 403 Forbidden\n",
      "id": "102690853823372288",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/home/main?un=%E7%8B%BC%E7%8D%BE%E8%B5%9D%E6%9C%88",
      "title": "狼獾赝月 的贴吧",
      "type": "feed",
      "url": "rsshub://baidu/tieba/user/%E7%8B%BC%E7%8D%BE%E8%B5%9D%E6%9C%88"
    },
    {
      "description": "垃圾一件而已 的贴吧 - Powered by RSSHub",
      "errorAt": "2026-06-06T22:26:57.932Z",
      "errorMessage": "[GET] \"https://tieba.baidu.com/home/main?un=KOKOKOKOKO巨蟹\": 403 Forbidden\n",
      "id": "86267569293295616",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/home/main?un=KOKOKOKOKO%E5%B7%A8%E8%9F%B9",
      "title": "垃圾一件而已 的贴吧",
      "type": "feed",
      "url": "rsshub://baidu/tieba/user/KOKOKOKOKO%E5%B7%A8%E8%9F%B9"
    }
  ]
}
```
