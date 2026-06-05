# 微博 - 博主

## Coverage
`index-only`

## Route
- Namespace: `weibo`
- Namespace Name: `微博`
- Route Path: `/weibo/user/:uid/:routeParams?`
- Route Name: `博主`
- Example: `/weibo/user/1195230310`
- URL: `weibo.com`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `DIYgod, iplusx, Rongronggg9, Konano`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
::: warning
部分博主仅登录可见，未提供 Cookie 的情况下不支持订阅，可以通过打开 `https://m.weibo.cn/u/:uid` 验证
:::

## Parameters
- `uid`: 用户 id, 博主主页打开控制台执行 `$CONFIG.oid` 获取
- `routeParams`: 额外参数；请参阅上面的说明和表格；特别地，当 `routeParams=1` 时开启微博视频显示


## Features
- `requireConfig`: [{"description": "", "name": "WEIBO_COOKIES", "optional": true}]
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `m.weibo.cn/u/:uid`
  - `m.weibo.cn/profile/:uid`
- `target`: `/user/:uid`
### Rule 2
- `source`:
  - `weibo.com/u/:uid`
- `target`: `/user/:uid`
### Rule 3
- `source`:
  - `www.weibo.com/u/:uid`
- `target`: `/user/:uid`

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "description": "::: warning\n部分博主仅登录可见，未提供 Cookie 的情况下不支持订阅，可以通过打开 `https://m.weibo.cn/u/:uid` 验证\n:::",
  "example": "/weibo/user/1195230310",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "",
        "name": "WEIBO_COOKIES",
        "optional": true
      }
    ],
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 51851,
  "location": "user.ts",
  "maintainers": [
    "DIYgod",
    "iplusx",
    "Rongronggg9",
    "Konano"
  ],
  "name": "博主",
  "parameters": {
    "routeParams": "额外参数；请参阅上面的说明和表格；特别地，当 `routeParams=1` 时开启微博视频显示",
    "uid": "用户 id, 博主主页打开控制台执行 `$CONFIG.oid` 获取"
  },
  "path": "/user/:uid/:routeParams?",
  "radar": [
    {
      "source": [
        "m.weibo.cn/u/:uid",
        "m.weibo.cn/profile/:uid"
      ],
      "target": "/user/:uid"
    },
    {
      "source": [
        "weibo.com/u/:uid"
      ],
      "target": "/user/:uid"
    },
    {
      "source": [
        "www.weibo.com/u/:uid"
      ],
      "target": "/user/:uid"
    }
  ],
  "topFeeds": [
    {
      "description": "产品经理；产品设计师；企业家；网络售货员；传奇网红 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55873602868576278",
      "image": "https://tvax2.sinaimg.cn/crop.0.0.600.600.180/008tj0GNly8i4ul6s2etyj30go0goq4h.jpg?KID=imgbed,tva&Expires=1780553888&ssig=5Y9kuqzLR3",
      "ownerUserId": null,
      "siteUrl": "https://weibo.com/7762107285/",
      "title": "罗永浩的十字路口的微博",
      "type": "feed",
      "url": "rsshub://weibo/user/7762107285"
    },
    {
      "description": "数码闲聊站的微博 - Powered by RSSHub",
      "errorAt": "2026-06-04T02:07:55.730Z",
      "errorMessage": "Cooling down before new visitor Cookies from https://m.weibo.cn/ may be fetched\nCould not find Chrome (ver. 136.0.7103.49). This can occur if either\n 1. you did not perform an installation before running the script (e.g. `npx puppeteer browsers install chrome`) or\n 2. your cache path is incorrectly configured (which is: /app/node_modules/.cache/puppeteer).\nFor (2), check out our guide on configuring puppeteer at https://pptr.dev/guides/configuration.\nCannot read properties of undefined (reading 'userInfo')\n530 <none>\n403 Forbidden\nbrowserType.connect: WebSocket error: getaddrinfo ENOTFOUND browserless\nCall log:\n  - <ws connecting> ws://browserless:3000/\n  - <ws error> ws://browserless:3000/ error getaddrinfo ENOTFOUND browserless\n  - <ws connect error> ws://browserless:3000/ getaddrinfo ENOTFOUND browserless\n  - <ws disconnected> ws://browserless:3000/ code=1006 reason=\n\nCannot read properties of undefined (reading 'userInfo')\nCooling down before new visitor Cookies from https://m.weibo.cn/ may be fetched\n",
      "id": "56574455833521152",
      "image": "https://tvax1.sinaimg.cn/crop.0.0.1080.1080.180/006BlblIly8gdim8sx8poj30u00u0adb.jpg?KID=imgbed,tva&Expires=1780518124&ssig=PfOuXdRf3G",
      "ownerUserId": null,
      "siteUrl": "https://weibo.com/6048569942/",
      "title": "数码闲聊站的微博",
      "type": "feed",
      "url": "rsshub://weibo/user/6048569942"
    }
  ],
  "view": 1
}
```
