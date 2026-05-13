# 哔哩哔哩 bilibili - 我的消息

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/message/sessions/:uid`
- Route Name: `我的消息`
- Example: `/bilibili/message/sessions/2267573`
- URL: `www.bilibili.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `pilgrimlyieu`
- Source Location: `message-sessions.ts`
- Source Module: `() => import('@/routes/bilibili/message-sessions.ts')`

## Description
:::warning
  用户消息需要 b 站登录后的 Cookie 值，所以只能自建，详情见部署页面的配置模块。
:::

## Parameters
- `uid`: 用户 id


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
  "description": ":::warning\n  用户消息需要 b 站登录后的 Cookie 值，所以只能自建，详情见部署页面的配置模块。\n:::",
  "example": "/bilibili/message/sessions/2267573",
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
  "location": "message-sessions.ts",
  "maintainers": [
    "pilgrimlyieu"
  ],
  "module": "() => import('@/routes/bilibili/message-sessions.ts')",
  "name": "我的消息",
  "parameters": {
    "uid": "用户 id"
  },
  "path": "/message/sessions/:uid"
}
```
