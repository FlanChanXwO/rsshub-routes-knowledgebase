# DN.com - News

## Coverage
`index-only`

## Route
- Namespace: `dn`
- Namespace Name: `DN.com`
- Route Path: `/:language/news/:category?`
- Route Name: `News`
- Example: `/dn/en-us/news`
- URL: `dn.com`
- Language: `en`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/dn/news.ts')`

## Description
#### Language

| English | 中文  |
| ------- | ----- |
| en-us   | zh-cn |

#### Category

| English Category     | 中文分类 | Category id |
| -------------------- | -------- | ----------- |
| The Latest           | 最新     |             |
| Industry Information | 行业资讯 | category-1  |
| Knowledge            | 域名知识 | category-2  |
| Investment           | 域名投资 | category-3  |

## Parameters
- `language`: Language, see below
- `category`: Category, see below, The Latest by default


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
  "description": "#### Language\n\n| English | 中文  |\n| ------- | ----- |\n| en-us   | zh-cn |\n\n#### Category\n\n| English Category     | 中文分类 | Category id |\n| -------------------- | -------- | ----------- |\n| The Latest           | 最新     |             |\n| Industry Information | 行业资讯 | category-1  |\n| Knowledge            | 域名知识 | category-2  |\n| Investment           | 域名投资 | category-3  |",
  "example": "/dn/en-us/news",
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
    "nczitzk"
  ],
  "module": "() => import('@/routes/dn/news.ts')",
  "name": "News",
  "parameters": {
    "category": "Category, see below, The Latest by default",
    "language": "Language, see below"
  },
  "path": "/:language/news/:category?"
}
```
