# 雪球 - 用户自选动态

## Coverage
`index-only`

## Route
- Namespace: `xueqiu`
- Namespace Name: `雪球`
- Route Path: `/user_stock/:id`
- Route Name: `用户自选动态`
- Example: `/xueqiu/user_stock/1247347556`
- URL: `danjuanapp.com`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `hillerliao`
- Source Location: `user-stock.ts`
- Source Module: `() => import('@/routes/xueqiu/user-stock.ts')`

## Description
::: warning
  用户自选动态需要登录后的 Cookie 值，所以只能自建，详情见部署页面的配置模块。
:::

## Parameters
- `id`: 用户 id, 可在用户主页 URL 中找到


## Features
- `requireConfig`: [{"description": "", "name": "XUEQIU_COOKIES"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `xueqiu.com/u/:id`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "::: warning\n  用户自选动态需要登录后的 Cookie 值，所以只能自建，详情见部署页面的配置模块。\n:::",
  "example": "/xueqiu/user_stock/1247347556",
  "features": {
    "antiCrawler": false,
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
  "location": "user-stock.ts",
  "maintainers": [
    "hillerliao"
  ],
  "module": "() => import('@/routes/xueqiu/user-stock.ts')",
  "name": "用户自选动态",
  "parameters": {
    "id": "用户 id, 可在用户主页 URL 中找到"
  },
  "path": "/user_stock/:id",
  "radar": [
    {
      "source": [
        "xueqiu.com/u/:id"
      ]
    }
  ]
}
```
