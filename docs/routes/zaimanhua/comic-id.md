# 再漫画 - 漫画更新

## Coverage
`index-only`

## Route
- Namespace: `zaimanhua`
- Namespace Name: `再漫画`
- Route Path: `/comic/:id`
- Route Name: `漫画更新`
- Example: `/zaimanhua/comic/57069`
- URL: `manhua.zaimanhua.com`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `kjasn`
- Source Location: `comic.ts`
- Source Module: `() => import('@/routes/zaimanhua/comic.ts')`

## Description
::: Warning
未登录用户无法获取到所有漫画，需要设置`ZAIMANHUA_TOKEN`环境变量以使用 API 授权访问。
且由于源网站本身的限制，建议尽量在部署于中国大陆网络内的 RSSHub 节点中使用本路由。若在海外网络环境中使用，即使设置了`ZAIMANHUA_TOKEN`环境变量，也可能无法获取全部漫画。
:::

## Parameters
- `id`: 漫画ID


## Features
- `requireConfig`: [{"description": "用户登录后，可以从浏览器开发者工具 Network 面板中的请求信息中获取 token，使用请求中的 `Authorization` 的值，完整设置为 `Bearer <token>`，或直接设置 token 并由路由自动补齐 `Bearer ` 前缀。", "name": "ZAIMANHUA_TOKEN", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `manhua.zaimanhua.com/details`
  - `manhua.zaimanhua.com/details/:id`
- `target`: `/comic/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "::: Warning\n未登录用户无法获取到所有漫画，需要设置`ZAIMANHUA_TOKEN`环境变量以使用 API 授权访问。\n且由于源网站本身的限制，建议尽量在部署于中国大陆网络内的 RSSHub 节点中使用本路由。若在海外网络环境中使用，即使设置了`ZAIMANHUA_TOKEN`环境变量，也可能无法获取全部漫画。\n:::",
  "example": "/zaimanhua/comic/57069",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": [
      {
        "description": "用户登录后，可以从浏览器开发者工具 Network 面板中的请求信息中获取 token，使用请求中的 `Authorization` 的值，完整设置为 `Bearer <token>`，或直接设置 token 并由路由自动补齐 `Bearer ` 前缀。",
        "name": "ZAIMANHUA_TOKEN",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "comic.ts",
  "maintainers": [
    "kjasn"
  ],
  "module": "() => import('@/routes/zaimanhua/comic.ts')",
  "name": "漫画更新",
  "parameters": {
    "id": "漫画ID"
  },
  "path": "/comic/:id",
  "radar": [
    {
      "source": [
        "manhua.zaimanhua.com/details",
        "manhua.zaimanhua.com/details/:id"
      ],
      "target": "/comic/:id"
    }
  ]
}
```
