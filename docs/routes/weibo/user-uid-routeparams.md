# 微博 - 博主

## Coverage
`index-only`

## Route
- Namespace: `weibo`
- Namespace Name: `微博`
- Route Path: `/user/:uid/:routeParams?`
- Route Name: `博主`
- Example: `/weibo/user/1195230310`
- URL: `weibo.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `DIYgod, iplusx, Rongronggg9, Konano`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/weibo/user.ts')`

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
    "social-media"
  ],
  "description": "::: warning\n  部分博主仅登录可见，未提供 Cookie 的情况下不支持订阅，可以通过打开 `https://m.weibo.cn/u/:uid` 验证\n:::",
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
  "location": "user.ts",
  "maintainers": [
    "DIYgod",
    "iplusx",
    "Rongronggg9",
    "Konano"
  ],
  "module": "() => import('@/routes/weibo/user.ts')",
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
  "view": 1
}
```
