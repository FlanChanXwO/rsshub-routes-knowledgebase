# 微博 - 最新关注时间线

## Coverage
`index-only`

## Route
- Namespace: `weibo`
- Namespace Name: `微博`
- Route Path: `/friends/:routeParams?`
- Route Name: `最新关注时间线`
- Example: `/weibo/friends`
- URL: `weibo.com/`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `CaoMeiYouRen`
- Source Location: `friends.ts`
- Source Module: `() => import('@/routes/weibo/friends.ts')`

## Description
::: warning
  此方案必须使用用户`Cookie`进行抓取

  因微博 cookies 的过期与更新方案未经验证，部署一次 Cookie 的有效时长未知

  微博用户 Cookie 的配置可参照部署文档
:::

## Parameters
- `routeParams`: 额外参数；请参阅上面的说明和表格


## Features
- `requireConfig`: [{"description": "", "name": "WEIBO_COOKIES", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `weibo.com/`
- `target`: `/friends`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "::: warning\n  此方案必须使用用户`Cookie`进行抓取\n\n  因微博 cookies 的过期与更新方案未经验证，部署一次 Cookie 的有效时长未知\n\n  微博用户 Cookie 的配置可参照部署文档\n:::",
  "example": "/weibo/friends",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "WEIBO_COOKIES",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "friends.ts",
  "maintainers": [
    "CaoMeiYouRen"
  ],
  "module": "() => import('@/routes/weibo/friends.ts')",
  "name": "最新关注时间线",
  "parameters": {
    "routeParams": "额外参数；请参阅上面的说明和表格"
  },
  "path": "/friends/:routeParams?",
  "radar": [
    {
      "source": [
        "weibo.com/"
      ],
      "target": "/friends"
    }
  ],
  "url": "weibo.com/"
}
```
