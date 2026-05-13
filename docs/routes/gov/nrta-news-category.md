# 国家能源局 - 分类

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/nrta/news/:category?`
- Route Name: `分类`
- Example: `/gov/nrta/news`
- URL: `www.nea.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `yuxinliu-alex`
- Source Location: `nrta/news.ts`
- Source Module: `() => import('@/routes/gov/nrta/news.ts')`

## Description
| 总局要闻 | 公告公示 | 工作动态 | 其他 |
| -------- | -------- | -------- | ---- |
| 112      | 113      | 114      |      |

## Parameters
- `category`: 资讯类别，可从地址中获取，默认为总局要闻


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 总局要闻 | 公告公示 | 工作动态 | 其他 |\n| -------- | -------- | -------- | ---- |\n| 112      | 113      | 114      |      |",
  "example": "/gov/nrta/news",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "nrta/news.ts",
  "maintainers": [
    "yuxinliu-alex"
  ],
  "module": "() => import('@/routes/gov/nrta/news.ts')",
  "name": "分类",
  "parameters": {
    "category": "资讯类别，可从地址中获取，默认为总局要闻"
  },
  "path": "/nrta/news/:category?"
}
```
