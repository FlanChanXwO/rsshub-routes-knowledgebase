# 品玩 - 话题动态

## Coverage
`index-only`

## Route
- Namespace: `pingwest`
- Namespace Name: `品玩`
- Route Path: `/tag/:tag/:type/:option?`
- Route Name: `话题动态`
- Example: `/pingwest/tag/ChinaJoy/1`
- URL: `pingwest.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `sanmmm`
- Source Location: `tag.ts`
- Source Module: `() => import('@/routes/pingwest/tag.ts')`

## Description
内容类型

| 最新 | 热门 |
| ---- | ---- |
| 1    | 2    |

  参数

  -   `fulltext`，全文输出，例如：`/pingwest/tag/ChinaJoy/1/fulltext`

::: tip
  该路由一次最多显示 30 条文章
:::

## Parameters
- `tag`: 话题名或话题id, 可从话题页url中得到
- `type`: 内容类型
- `option`: 参数, 默认无


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
    "new-media"
  ],
  "description": "内容类型\n\n| 最新 | 热门 |\n| ---- | ---- |\n| 1    | 2    |\n\n  参数\n\n  -   `fulltext`，全文输出，例如：`/pingwest/tag/ChinaJoy/1/fulltext`\n\n::: tip\n  该路由一次最多显示 30 条文章\n:::",
  "example": "/pingwest/tag/ChinaJoy/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "tag.ts",
  "maintainers": [
    "sanmmm"
  ],
  "module": "() => import('@/routes/pingwest/tag.ts')",
  "name": "话题动态",
  "parameters": {
    "option": "参数, 默认无",
    "tag": "话题名或话题id, 可从话题页url中得到",
    "type": "内容类型"
  },
  "path": "/tag/:tag/:type/:option?"
}
```
