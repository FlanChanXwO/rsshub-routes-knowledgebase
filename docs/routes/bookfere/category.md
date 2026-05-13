# 书伴 - 分类

## Coverage
`index-only`

## Route
- Namespace: `bookfere`
- Namespace Name: `书伴`
- Route Path: `/:category`
- Route Name: `分类`
- Example: `/bookfere/skills`
- URL: `bookfere.com`
- Language: `zh-CN`
- Categories: `reading`
- Maintainers: `OdinZhang`
- Source Location: `category.ts`
- Source Module: `() => import('@/routes/bookfere/category.ts')`

## Description
| 每周一书 | 使用技巧 | 图书推荐 | 新闻速递 | 精选短文 |
| -------- | -------- | -------- | -------- | -------- |
| weekly   | skills   | books    | news     | essay    |

## Parameters
- `category`: {"description": "分类名", "options": [{"label": "每周一书", "value": "weekly"}, {"label": "使用技巧", "value": "skills"}, {"label": "图书推荐", "value": "books"}, {"label": "新闻速递", "value": "news"}, {"label": "精选短文", "value": "essay"}]}


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
    "reading"
  ],
  "description": "| 每周一书 | 使用技巧 | 图书推荐 | 新闻速递 | 精选短文 |\n| -------- | -------- | -------- | -------- | -------- |\n| weekly   | skills   | books    | news     | essay    |",
  "example": "/bookfere/skills",
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
    "OdinZhang"
  ],
  "module": "() => import('@/routes/bookfere/category.ts')",
  "name": "分类",
  "parameters": {
    "category": {
      "description": "分类名",
      "options": [
        {
          "label": "每周一书",
          "value": "weekly"
        },
        {
          "label": "使用技巧",
          "value": "skills"
        },
        {
          "label": "图书推荐",
          "value": "books"
        },
        {
          "label": "新闻速递",
          "value": "news"
        },
        {
          "label": "精选短文",
          "value": "essay"
        }
      ]
    }
  },
  "path": "/:category",
  "view": 0
}
```
