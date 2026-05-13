# 月幕 Galgame - 文章

## Coverage
`index-only`

## Route
- Namespace: `ymgal`
- Namespace Name: `月幕 Galgame`
- Route Path: `/article/:type?`
- Route Name: `文章`
- Example: `/ymgal/article`
- URL: `ymgal.games`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `SunBK201`
- Source Location: `article.ts`
- Source Module: `() => import('@/routes/ymgal/article.ts')`

## Description
| 全部文章 | 资讯 | 专栏   |
| -------- | ---- | ------ |
| all      | news | column |

## Parameters
- `type`: 文章类型


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
    "anime"
  ],
  "description": "| 全部文章 | 资讯 | 专栏   |\n| -------- | ---- | ------ |\n| all      | news | column |",
  "example": "/ymgal/article",
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
    "SunBK201"
  ],
  "module": "() => import('@/routes/ymgal/article.ts')",
  "name": "文章",
  "parameters": {
    "type": "文章类型"
  },
  "path": "/article/:type?"
}
```
