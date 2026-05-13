# 微博 - 个人时间线

## Coverage
`index-only`

## Route
- Namespace: `weibo`
- Namespace Name: `微博`
- Route Path: `/timeline/:uid/:feature?/:routeParams?`
- Route Name: `个人时间线`
- Example: `/weibo/timeline/3306934123`
- URL: `weibo.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `zytomorrow, DIYgod, Rongronggg9`
- Source Location: `timeline.ts`
- Source Module: `() => import('@/routes/weibo/timeline.ts')`

## Description
::: warning
  需要对应用户打开页面进行授权生成 token 才能生成内容

  自部署需要申请并配置微博 key，具体见部署文档
:::

## Parameters
- `uid`: 用户的uid
- `feature`: 过滤类型ID，0：全部、1：原创、2：图片、3：视频、4：音乐，默认为0。
- `routeParams`: 额外参数；请参阅上面的说明和表格


## Features
- `requireConfig`: [{"description": "", "name": "WEIBO_APP_KEY"}, {"description": "", "name": "WEIBO_REDIRECT_URL"}]
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
  "description": "::: warning\n  需要对应用户打开页面进行授权生成 token 才能生成内容\n\n  自部署需要申请并配置微博 key，具体见部署文档\n:::",
  "example": "/weibo/timeline/3306934123",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "WEIBO_APP_KEY"
      },
      {
        "description": "",
        "name": "WEIBO_REDIRECT_URL"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "timeline.ts",
  "maintainers": [
    "zytomorrow",
    "DIYgod",
    "Rongronggg9"
  ],
  "module": "() => import('@/routes/weibo/timeline.ts')",
  "name": "个人时间线",
  "parameters": {
    "feature": "过滤类型ID，0：全部、1：原创、2：图片、3：视频、4：音乐，默认为0。",
    "routeParams": "额外参数；请参阅上面的说明和表格",
    "uid": "用户的uid"
  },
  "path": "/timeline/:uid/:feature?/:routeParams?"
}
```
