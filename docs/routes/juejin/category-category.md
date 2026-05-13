# 掘金 - 分类

## Coverage
`index-only`

## Route
- Namespace: `juejin`
- Namespace Name: `掘金`
- Route Path: `/category/:category`
- Route Name: `分类`
- Example: `/juejin/category/frontend`
- URL: `juejin.cn`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `DIYgod`
- Source Location: `category.ts`
- Source Module: `() => import('@/routes/juejin/category.ts')`

## Description
| 后端    | 前端     | Android | iOS | 人工智能 | 开发工具 | 代码人生 | 阅读    |
| ------- | -------- | ------- | --- | -------- | -------- | -------- | ------- |
| backend | frontend | android | ios | ai       | freebie  | career   | article |

## Parameters
- `category`: 分类名


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `juejin.cn/:category`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "| 后端    | 前端     | Android | iOS | 人工智能 | 开发工具 | 代码人生 | 阅读    |\n| ------- | -------- | ------- | --- | -------- | -------- | -------- | ------- |\n| backend | frontend | android | ios | ai       | freebie  | career   | article |",
  "example": "/juejin/category/frontend",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "category.ts",
  "maintainers": [
    "DIYgod"
  ],
  "module": "() => import('@/routes/juejin/category.ts')",
  "name": "分类",
  "parameters": {
    "category": "分类名"
  },
  "path": "/category/:category",
  "radar": [
    {
      "source": [
        "juejin.cn/:category"
      ]
    }
  ]
}
```
