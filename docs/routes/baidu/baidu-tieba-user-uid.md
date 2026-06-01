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
      "description": "垃圾一件而已 的贴吧 - Powered by RSSHub",
      "errorAt": "2026-04-24T08:25:24.210Z",
      "errorMessage": "[GET] \"https://tieba.baidu.com/home/main?un=KOKOKOKOKO巨蟹\": 403 Forbidden\n",
      "id": "86267569293295616",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/home/main?un=KOKOKOKOKO%E5%B7%A8%E8%9F%B9",
      "title": "垃圾一件而已 的贴吧",
      "type": "feed",
      "url": "rsshub://baidu/tieba/user/KOKOKOKOKO%E5%B7%A8%E8%9F%B9"
    },
    {
      "description": "阳光下的咪西 的贴吧 - Powered by RSSHub",
      "errorAt": "2026-04-05T11:51:29.923Z",
      "errorMessage": "[GET] \"https://tieba.baidu.com/home/main?un=阳光下的咪西\": 403 Forbidden\n",
      "id": "69911701157875712",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://tieba.baidu.com/home/main?un=%E9%98%B3%E5%85%89%E4%B8%8B%E7%9A%84%E5%92%AA%E8%A5%BF",
      "title": "阳光下的咪西 的贴吧",
      "type": "feed",
      "url": "rsshub://baidu/tieba/user/%E9%98%B3%E5%85%89%E4%B8%8B%E7%9A%84%E5%92%AA%E8%A5%BF"
    }
  ]
}
```
