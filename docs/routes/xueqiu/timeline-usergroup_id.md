# 雪球 - 用户关注时间线

## Coverage
`index-only`

## Route
- Namespace: `xueqiu`
- Namespace Name: `雪球`
- Route Path: `/timeline/:usergroup_id?`
- Route Name: `用户关注时间线`
- Example: `/xueqiu/timeline/`
- URL: `danjuanapp.com`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `ErnestDong`
- Source Location: `timeline.ts`
- Source Module: `() => import('@/routes/xueqiu/timeline.ts')`

## Description
::: warning
  用户关注动态需要登录后的 Cookie 值，所以只能自建，详情见部署页面的配置模块。
:::

| -1   | -2       | 1             |
| ---- | -------- | ------------- |
| 全部 | 关注精选 | 自定义第 1 组 |

## Parameters
- `usergroup_id`: 用户组 ID，-1 为全部关注用户


## Features
- `requireConfig`: [{"description": "", "name": "XUEQIU_COOKIES"}]
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "::: warning\n  用户关注动态需要登录后的 Cookie 值，所以只能自建，详情见部署页面的配置模块。\n:::\n\n| -1   | -2       | 1             |\n| ---- | -------- | ------------- |\n| 全部 | 关注精选 | 自定义第 1 组 |",
  "example": "/xueqiu/timeline/",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "",
        "name": "XUEQIU_COOKIES"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "timeline.ts",
  "maintainers": [
    "ErnestDong"
  ],
  "module": "() => import('@/routes/xueqiu/timeline.ts')",
  "name": "用户关注时间线",
  "parameters": {
    "usergroup_id": "用户组 ID，-1 为全部关注用户"
  },
  "path": "/timeline/:usergroup_id?"
}
```
