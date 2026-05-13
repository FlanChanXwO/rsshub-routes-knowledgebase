# 广州日报 - 客户端

## Coverage
`index-only`

## Route
- Namespace: `gzdaily`
- Namespace Name: `广州日报`
- Route Path: `/app/:column?`
- Route Name: `客户端`
- Example: `/gzdaily/app/74`
- URL: `gzdaily.cn`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `TimWu007`
- Source Location: `app.tsx`
- Source Module: `() => import('@/routes/gzdaily/app.tsx')`

## Description
::: tip
  在北京时间深夜可能无法获取内容。
:::

  常用栏目 ID：

| 栏目名 | ID   |
| ------ | ---- |
| 首页   | 74   |
| 时局   | 374  |
| 广州   | 371  |
| 大湾区 | 397  |
| 城区   | 2980 |

## Parameters
- `column`: 栏目 ID，点击对应栏目后在地址栏找到


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
    "traditional-media"
  ],
  "description": "::: tip\n  在北京时间深夜可能无法获取内容。\n:::\n\n  常用栏目 ID：\n\n| 栏目名 | ID   |\n| ------ | ---- |\n| 首页   | 74   |\n| 时局   | 374  |\n| 广州   | 371  |\n| 大湾区 | 397  |\n| 城区   | 2980 |",
  "example": "/gzdaily/app/74",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "app.tsx",
  "maintainers": [
    "TimWu007"
  ],
  "module": "() => import('@/routes/gzdaily/app.tsx')",
  "name": "客户端",
  "parameters": {
    "column": "栏目 ID，点击对应栏目后在地址栏找到"
  },
  "path": "/app/:column?"
}
```
