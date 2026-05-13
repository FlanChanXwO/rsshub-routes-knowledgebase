# 知乎 - 用户关注时间线

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/timeline`
- Route Name: `用户关注时间线`
- Example: `/zhihu/timeline`
- URL: `www.zhihu.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `SeanChao`
- Source Location: `timeline.ts`
- Source Module: `() => import('@/routes/zhihu/timeline.ts')`

## Description
::: warning
  用户关注动态需要登录后的 Cookie 值，所以只能自建，详情见部署页面的配置模块。
:::

## Parameters
_None_


## Features
- `requireConfig`: [{"description": "", "name": "ZHIHU_COOKIES"}]
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
    "social-media"
  ],
  "description": "::: warning\n  用户关注动态需要登录后的 Cookie 值，所以只能自建，详情见部署页面的配置模块。\n:::",
  "example": "/zhihu/timeline",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "",
        "name": "ZHIHU_COOKIES"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "timeline.ts",
  "maintainers": [
    "SeanChao"
  ],
  "module": "() => import('@/routes/zhihu/timeline.ts')",
  "name": "用户关注时间线",
  "parameters": {},
  "path": "/timeline"
}
```
