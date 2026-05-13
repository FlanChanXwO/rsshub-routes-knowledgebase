# 大眼仔旭 - 分类

## Coverage
`index-only`

## Route
- Namespace: `dayanzai`
- Namespace Name: `大眼仔旭`
- Route Path: `/:category/:fulltext?`
- Route Name: `分类`
- Example: `/dayanzai/windows`
- URL: `dayanzai.me`
- Language: `zh-CN`
- Categories: `blog`
- Maintainers: `None`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/dayanzai/index.ts')`

## Description
| 微软应用 | 安卓应用 | 教程资源 | 其他资源 |
| -------- | -------- | -------- | -------- |
| windows  | android  | tutorial | other    |

## Parameters
- `category`: 分类
- `fulltext`: 是否获取全文，需要获取则传入参数`y`


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
  - `dayanzai.me/:category`
  - `dayanzai.me/:category/*`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "description": "| 微软应用 | 安卓应用 | 教程资源 | 其他资源 |\n| -------- | -------- | -------- | -------- |\n| windows  | android  | tutorial | other    |",
  "example": "/dayanzai/windows",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [],
  "module": "() => import('@/routes/dayanzai/index.ts')",
  "name": "分类",
  "parameters": {
    "category": "分类",
    "fulltext": "是否获取全文，需要获取则传入参数`y`"
  },
  "path": "/:category/:fulltext?",
  "radar": [
    {
      "source": [
        "dayanzai.me/:category",
        "dayanzai.me/:category/*"
      ],
      "target": "/:category"
    }
  ]
}
```
