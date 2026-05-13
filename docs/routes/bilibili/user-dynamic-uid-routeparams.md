# 哔哩哔哩 bilibili - UP 主动态

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/user/dynamic/:uid/:routeParams?`
- Route Name: `UP 主动态`
- Example: `/bilibili/user/dynamic/2267573`
- URL: `www.bilibili.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `DIYgod, zytomorrow, CaoMeiYouRen, JimenezLi`
- Source Location: `dynamic.ts`
- Source Module: `() => import('@/routes/bilibili/dynamic.ts')`

## Description
_None_

## Parameters
- `uid`: 用户 id, 可在 UP 主主页中找到
- `routeParams`: | 键         | 含义                              | 接受的值       | 默认值 |
| ---------- | --------------------------------- | -------------- | ------ |
| showEmoji  | 显示或隐藏表情图片                | 0/1/true/false | false  |
| embed      | 默认开启内嵌视频                  | 0/1/true/false |  true  |
| useAvid    | 视频链接使用 AV 号 (默认为 BV 号) | 0/1/true/false | false  |
| directLink | 使用内容直链                      | 0/1/true/false | false  |
| hideGoods  | 隐藏带货动态                      | 0/1/true/false | false  |
| offset     | 偏移状态                         | string         | ""  |

用例：`/bilibili/user/dynamic/2267573/showEmoji=1&embed=0&useAvid=1`


## Features
- `requireConfig`: [{"description": "如果没有此配置，那么必须开启 puppeteer 支持；BILIBILI_COOKIE_{uid}: 用于用户关注动态系列路由，对应 uid 的 b 站用户登录后的 Cookie 值，`{uid}` 替换为 uid，如 `BILIBILI_COOKIE_2267573`，获取方式：\n1.  打开 [https://api.vc.bilibili.com/dynamic_svr/v1/dynamic_svr/dynamic_new?uid=0&type=8](https://api.vc.bilibili.com/dynamic_svr/v1/dynamic_svr/dynamic_new?uid=0&type=8)\n2.  打开控制台，切换到 Network 面板，刷新\n3.  点击 dynamic_new 请求，找到 Cookie\n4.  视频和专栏，UP 主粉丝及关注只要求 `SESSDATA` 字段，动态需复制整段 Cookie", "name": "BILIBILI_COOKIE_*", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `space.bilibili.com/:uid`
- `target`: `/user/dynamic/:uid`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/bilibili/user/dynamic/2267573",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "如果没有此配置，那么必须开启 puppeteer 支持；BILIBILI_COOKIE_{uid}: 用于用户关注动态系列路由，对应 uid 的 b 站用户登录后的 Cookie 值，`{uid}` 替换为 uid，如 `BILIBILI_COOKIE_2267573`，获取方式：\n1.  打开 [https://api.vc.bilibili.com/dynamic_svr/v1/dynamic_svr/dynamic_new?uid=0&type=8](https://api.vc.bilibili.com/dynamic_svr/v1/dynamic_svr/dynamic_new?uid=0&type=8)\n2.  打开控制台，切换到 Network 面板，刷新\n3.  点击 dynamic_new 请求，找到 Cookie\n4.  视频和专栏，UP 主粉丝及关注只要求 `SESSDATA` 字段，动态需复制整段 Cookie",
        "name": "BILIBILI_COOKIE_*",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "dynamic.ts",
  "maintainers": [
    "DIYgod",
    "zytomorrow",
    "CaoMeiYouRen",
    "JimenezLi"
  ],
  "module": "() => import('@/routes/bilibili/dynamic.ts')",
  "name": "UP 主动态",
  "parameters": {
    "routeParams": "\n| 键         | 含义                              | 接受的值       | 默认值 |\n| ---------- | --------------------------------- | -------------- | ------ |\n| showEmoji  | 显示或隐藏表情图片                | 0/1/true/false | false  |\n| embed      | 默认开启内嵌视频                  | 0/1/true/false |  true  |\n| useAvid    | 视频链接使用 AV 号 (默认为 BV 号) | 0/1/true/false | false  |\n| directLink | 使用内容直链                      | 0/1/true/false | false  |\n| hideGoods  | 隐藏带货动态                      | 0/1/true/false | false  |\n| offset     | 偏移状态                         | string         | \"\"  |\n\n用例：`/bilibili/user/dynamic/2267573/showEmoji=1&embed=0&useAvid=1`",
    "uid": "用户 id, 可在 UP 主主页中找到"
  },
  "path": "/user/dynamic/:uid/:routeParams?",
  "radar": [
    {
      "source": [
        "space.bilibili.com/:uid"
      ],
      "target": "/user/dynamic/:uid"
    }
  ],
  "view": 1
}
```
