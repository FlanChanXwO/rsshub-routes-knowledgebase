# 米哈游 - 米游社 - 用户关注动态

## Coverage
`index-only`

## Route
- Namespace: `mihoyo`
- Namespace Name: `米哈游`
- Route Path: `/bbs/timeline`
- Route Name: `米游社 - 用户关注动态`
- Example: `/mihoyo/bbs/timeline`
- URL: `genshin.hoyoverse.com`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `CaoMeiYouRen`
- Source Location: `bbs/timeline.ts`
- Source Module: `() => import('@/routes/mihoyo/bbs/timeline.ts')`

## Description
::: warning
  用户关注动态需要米游社登录后的 Cookie 值，所以只能自建，详情见部署页面的配置模块。
:::

## Parameters
_None_


## Features
- `requireConfig`: [{"description": "", "name": "MIHOYO_COOKIE"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `miyoushe.com/:game/timeline`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "::: warning\n  用户关注动态需要米游社登录后的 Cookie 值，所以只能自建，详情见部署页面的配置模块。\n:::",
  "example": "/mihoyo/bbs/timeline",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "MIHOYO_COOKIE"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "bbs/timeline.ts",
  "maintainers": [
    "CaoMeiYouRen"
  ],
  "module": "() => import('@/routes/mihoyo/bbs/timeline.ts')",
  "name": "米游社 - 用户关注动态",
  "parameters": {},
  "path": "/bbs/timeline",
  "radar": [
    {
      "source": [
        "miyoushe.com/:game/timeline"
      ]
    }
  ]
}
```
