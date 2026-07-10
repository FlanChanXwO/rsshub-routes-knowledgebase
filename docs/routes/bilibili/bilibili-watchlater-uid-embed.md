# 哔哩哔哩 bilibili - 用户稍后再看

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/watchlater/:uid/:embed?`
- Route Name: `用户稍后再看`
- Example: `/bilibili/watchlater/2267573`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `JimenezLi`
- Source Location: `watchlater.ts`
- Source Module: `_None_`

## Description
::: warning
用户稍后再看需要 b 站登录后的 Cookie 值，所以只能自建，详情见部署页面的配置模块。
:::

## Parameters
- `uid`: 用户 id
- `embed`: 默认为开启内嵌视频, 任意值为关闭


## Features
- `requireConfig`: [{"description": "BILIBILI_COOKIE_{uid}: 用于用户关注动态系列路由，对应 uid 的 b 站用户登录后的 Cookie 值，`{uid}` 替换为 uid，如 `BILIBILI_COOKIE_2267573`，获取方式：\n    1.  打开 [https://api.vc.bilibili.com/dynamic_svr/v1/dynamic_svr/dynamic_new?uid=0&type=8](https://api.vc.bilibili.com/dynamic_svr/v1/dynamic_svr/dynamic_new?uid=0&type=8)\n    2.  打开控制台，切换到 Network 面板，刷新\n    3.  点击 dynamic_new 请求，找到 Cookie\n    4.  视频和专栏，UP 主粉丝及关注只要求 `SESSDATA` 字段，动态需复制整段 Cookie", "name": "BILIBILI_COOKIE_*"}]
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
    "social-media"
  ],
  "description": "::: warning\n用户稍后再看需要 b 站登录后的 Cookie 值，所以只能自建，详情见部署页面的配置模块。\n:::",
  "example": "/bilibili/watchlater/2267573",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "BILIBILI_COOKIE_{uid}: 用于用户关注动态系列路由，对应 uid 的 b 站用户登录后的 Cookie 值，`{uid}` 替换为 uid，如 `BILIBILI_COOKIE_2267573`，获取方式：\n    1.  打开 [https://api.vc.bilibili.com/dynamic_svr/v1/dynamic_svr/dynamic_new?uid=0&type=8](https://api.vc.bilibili.com/dynamic_svr/v1/dynamic_svr/dynamic_new?uid=0&type=8)\n    2.  打开控制台，切换到 Network 面板，刷新\n    3.  点击 dynamic_new 请求，找到 Cookie\n    4.  视频和专栏，UP 主粉丝及关注只要求 `SESSDATA` 字段，动态需复制整段 Cookie",
        "name": "BILIBILI_COOKIE_*"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "watchlater.ts",
  "maintainers": [
    "JimenezLi"
  ],
  "name": "用户稍后再看",
  "parameters": {
    "embed": "默认为开启内嵌视频, 任意值为关闭",
    "uid": "用户 id"
  },
  "path": "/watchlater/:uid/:embed?",
  "topFeeds": []
}
```
