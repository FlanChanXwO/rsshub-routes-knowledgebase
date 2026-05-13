# 知乎 - 用户关注时间线

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/zhihu/timeline`
- Route Name: `用户关注时间线`
- Example: `/zhihu/timeline`
- URL: `www.zhihu.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `SeanChao`
- Source Location: `timeline.ts`
- Source Module: `_None_`

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
  "description": "::: warning\n用户关注动态需要登录后的 Cookie 值，所以只能自建，详情见部署页面的配置模块。\n:::",
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
  "heat": 3,
  "location": "timeline.ts",
  "maintainers": [
    "SeanChao"
  ],
  "name": "用户关注时间线",
  "parameters": {},
  "path": "/timeline",
  "topFeeds": [
    {
      "description": "知乎关注动态 - Powered by RSSHub",
      "errorAt": "2025-03-15T20:29:03.878Z",
      "errorMessage": "缺少知乎用户登录后的 Cookie 值\n",
      "id": "122563562492618752",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/follow",
      "title": "知乎关注动态",
      "type": "feed",
      "url": "rsshub://zhihu/timeline"
    }
  ]
}
```
