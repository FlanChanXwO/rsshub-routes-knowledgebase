# The Initium - App

## Coverage
`index-only`

## Route
- Namespace: `theinitium`
- Namespace Name: `The Initium`
- Route Path: `/app/:category?`
- Route Name: `App`
- Example: `/theinitium/app`
- URL: `theinitium.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `quiniapiezoelectricity, pseudoyu`
- Source Location: `app.ts`
- Source Module: `() => import('@/routes/theinitium/app.ts')`

## Description
Category 栏目：

| ----- | 简体中文     | 繁體中文      |
| ----- | ----------------- | ---------------- |
| 最新   | latest_sc | latest_tc |
| 日报   | daily_brief_sc | daily_brief_tc |
| 速递   | whats_new_sc | whats_new_tc |
| 专题   | report_sc | report_tc |
| 评论   | opinion_sc | opinion_tc |
| 国际   | international_sc | international_tc |
| 大陆   | mainland_sc | mainland_tc |
| 香港   | hongkong_sc | hongkong_tc |
| 台湾   | taiwan_sc | taiwan_tc |

:::tip
原 App 路由已迁移至 Ghost CMS API。播客（article_audio）分类已停用，请改用 `/theinitium/channel` 路由。
:::

## Parameters
- `category`: Category, see below, latest_sc by default


## Features
- `requireConfig`: [{"description": "端传媒会员登录后的 Cookie，用于获取付费文章全文。", "name": "INITIUM_MEMBER_COOKIE", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `theinitium.com/latest/`
- `target`: `/app/latest_sc`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "Category 栏目：\n\n| ----- | 简体中文     | 繁體中文      |\n| ----- | ----------------- | ---------------- |\n| 最新   | latest_sc | latest_tc |\n| 日报   | daily_brief_sc | daily_brief_tc |\n| 速递   | whats_new_sc | whats_new_tc |\n| 专题   | report_sc | report_tc |\n| 评论   | opinion_sc | opinion_tc |\n| 国际   | international_sc | international_tc |\n| 大陆   | mainland_sc | mainland_tc |\n| 香港   | hongkong_sc | hongkong_tc |\n| 台湾   | taiwan_sc | taiwan_tc |\n\n:::tip\n原 App 路由已迁移至 Ghost CMS API。播客（article_audio）分类已停用，请改用 `/theinitium/channel` 路由。\n:::",
  "example": "/theinitium/app",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "端传媒会员登录后的 Cookie，用于获取付费文章全文。",
        "name": "INITIUM_MEMBER_COOKIE",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "app.ts",
  "maintainers": [
    "quiniapiezoelectricity",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/theinitium/app.ts')",
  "name": "App",
  "parameters": {
    "category": "Category, see below, latest_sc by default"
  },
  "path": "/app/:category?",
  "radar": [
    {
      "source": [
        "theinitium.com/latest/"
      ],
      "target": "/app/latest_sc"
    }
  ]
}
```
