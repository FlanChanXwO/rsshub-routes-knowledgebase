# 哈尔滨工业大学（深圳） - 新闻中心

## Coverage
`index-only`

## Route
- Namespace: `hitsz`
- Namespace Name: `哈尔滨工业大学（深圳）`
- Route Path: `/article/:category?`
- Route Name: `新闻中心`
- Example: `/hitsz/article/id-74`
- URL: `hitsz.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `xandery-geek`
- Source Location: `article.ts`
- Source Module: `() => import('@/routes/hitsz/article.ts')`

## Description
| 校区要闻 | 媒体报道 | 综合新闻 | 校园动态 | 讲座论坛 | 热点专题 | 招标信息 | 重要关注 |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| id-116   | id-80    | id-75    | id-77    | id-78    | id-79    | id-81    | id-124   |

## Parameters
- `category`: 分类名，默认为校园动态


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
    "university"
  ],
  "description": "| 校区要闻 | 媒体报道 | 综合新闻 | 校园动态 | 讲座论坛 | 热点专题 | 招标信息 | 重要关注 |\n| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |\n| id-116   | id-80    | id-75    | id-77    | id-78    | id-79    | id-81    | id-124   |",
  "example": "/hitsz/article/id-74",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "article.ts",
  "maintainers": [
    "xandery-geek"
  ],
  "module": "() => import('@/routes/hitsz/article.ts')",
  "name": "新闻中心",
  "parameters": {
    "category": "分类名，默认为校园动态"
  },
  "path": "/article/:category?"
}
```
