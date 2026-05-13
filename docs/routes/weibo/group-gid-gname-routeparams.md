# 微博 - 自定义分组

## Coverage
`index-only`

## Route
- Namespace: `weibo`
- Namespace Name: `微博`
- Route Path: `/group/:gid/:gname?/:routeParams?`
- Route Name: `自定义分组`
- Example: `/weibo/group/4541216424989965`
- URL: `weibo.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `monologconnor, Rongronggg9`
- Source Location: `group.ts`
- Source Module: `() => import('@/routes/weibo/group.ts')`

## Description
::: warning
  由于微博官方未提供自定义分组相关 api, 此方案必须使用用户`Cookie`进行抓取

  因微博 cookies 的过期与更新方案未经验证，部署一次 Cookie 的有效时长未知

  微博用户 Cookie 的配置可参照部署文档
:::

## Parameters
- `gid`: 分组id, 在网页版分组地址栏末尾`?gid=`处获取
- `gname`: 分组显示名称; 默认为: `微博分组`
- `routeParams`: 额外参数；请参阅上面的说明和表格


## Features
- `requireConfig`: [{"description": "", "name": "WEIBO_COOKIES", "optional": true}]
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
  "description": "::: warning\n  由于微博官方未提供自定义分组相关 api, 此方案必须使用用户`Cookie`进行抓取\n\n  因微博 cookies 的过期与更新方案未经验证，部署一次 Cookie 的有效时长未知\n\n  微博用户 Cookie 的配置可参照部署文档\n:::",
  "example": "/weibo/group/4541216424989965",
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
  "location": "group.ts",
  "maintainers": [
    "monologconnor",
    "Rongronggg9"
  ],
  "module": "() => import('@/routes/weibo/group.ts')",
  "name": "自定义分组",
  "parameters": {
    "gid": "分组id, 在网页版分组地址栏末尾`?gid=`处获取",
    "gname": "分组显示名称; 默认为: `微博分组`",
    "routeParams": "额外参数；请参阅上面的说明和表格"
  },
  "path": "/group/:gid/:gname?/:routeParams?"
}
```
