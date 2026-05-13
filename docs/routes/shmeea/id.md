# 上海市教育考试院 - 消息

## Coverage
`index-only`

## Route
- Namespace: `shmeea`
- Namespace Name: `上海市教育考试院`
- Route Path: `/:id?`
- Route Name: `消息`
- Example: `/shmeea/08000`
- URL: `www.shmeea.edu.cn`
- Language: `zh-CN`
- Categories: `study`
- Maintainers: `jialinghui, Misaka13514`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/shmeea/index.ts')`

## Description
::: tip
  例如：消息速递的网址为 `https://www.shmeea.edu.cn/page/08000/index.html`，则页面 ID 为 `08000`。
:::

::: warning
  暂不支持大类分类和[院内动态](https://www.shmeea.edu.cn/page/19000/index.html)
:::

## Parameters
- `id`: 页面 ID，可在 URL 中找到，默认为消息速递


## Features
- `requireConfig`: false
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
    "study"
  ],
  "description": "::: tip\n  例如：消息速递的网址为 `https://www.shmeea.edu.cn/page/08000/index.html`，则页面 ID 为 `08000`。\n:::\n\n::: warning\n  暂不支持大类分类和[院内动态](https://www.shmeea.edu.cn/page/19000/index.html)\n:::",
  "example": "/shmeea/08000",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "jialinghui",
    "Misaka13514"
  ],
  "module": "() => import('@/routes/shmeea/index.ts')",
  "name": "消息",
  "parameters": {
    "id": "页面 ID，可在 URL 中找到，默认为消息速递"
  },
  "path": "/:id?"
}
```
