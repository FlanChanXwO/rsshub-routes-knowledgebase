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
      "description": "dengchunlai 的贴吧 - Powered by RSSHub",
      "errorAt": "2026-04-24T13:11:20.764Z",
      "errorMessage": "[GET] \"https://tieba.baidu.com/home/main?un=dengchunlai\": 403 Forbidden\n",
      "id": "104695101579488257",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/home/main?un=dengchunlai",
      "title": "dengchunlai 的贴吧",
      "type": "feed",
      "url": "rsshub://baidu/tieba/user/dengchunlai"
    },
    {
      "description": "K盘音 的贴吧 - Powered by RSSHub",
      "errorAt": "2025-11-16T04:13:10.675Z",
      "errorMessage": "[GET] \"https://tieba.baidu.com/home/main?un=TheKickInside\": 403 Forbidden\n",
      "id": "197372964709496832",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/home/main?un=TheKickInside",
      "title": "K盘音 的贴吧",
      "type": "feed",
      "url": "rsshub://baidu/tieba/user/TheKickInside"
    }
  ]
}
```
