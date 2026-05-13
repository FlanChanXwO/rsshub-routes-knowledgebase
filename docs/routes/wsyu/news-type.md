# 武昌首义学院 - 新闻中心

## Coverage
`index-only`

## Route
- Namespace: `wsyu`
- Namespace Name: `武昌首义学院`
- Route Path: `/news/:type?`
- Route Name: `新闻中心`
- Example: `/wsyu/news/xxyw`
- URL: `www.wsyu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `Derekmini`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/wsyu/news.ts')`

## Description
| 学校要闻 | 综合新闻 | 媒体聚焦 |
| -------- | -------- | -------- |
| xxyw     | zhxw     | mtjj     |

## Parameters
- `type`: 分类，默认为 `xxyw`


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
  "description": "| 学校要闻 | 综合新闻 | 媒体聚焦 |\n| -------- | -------- | -------- |\n| xxyw     | zhxw     | mtjj     |",
  "example": "/wsyu/news/xxyw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "Derekmini"
  ],
  "module": "() => import('@/routes/wsyu/news.ts')",
  "name": "新闻中心",
  "parameters": {
    "type": "分类，默认为 `xxyw`"
  },
  "path": "/news/:type?"
}
```
