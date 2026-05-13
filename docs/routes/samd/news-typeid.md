# 深圳市医疗器械行业协会 - 资讯信息

## Coverage
`index-only`

## Route
- Namespace: `samd`
- Namespace Name: `深圳市医疗器械行业协会`
- Route Path: `/news/:typeId`
- Route Name: `资讯信息`
- Example: `/samd/news/440`
- URL: `www.samd.org.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `hualiong`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/samd/news.ts')`

## Description
| 行业资讯 | 协会动态 | 重要通知 | 政策法规 |
| --- | --- | --- | --- |
| 434 | 436 | 438 | 440 |

## Parameters
- `type`: 文章类型ID，见下表


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
    "government"
  ],
  "description": "| 行业资讯 | 协会动态 | 重要通知 | 政策法规 |\n| --- | --- | --- | --- |\n| 434 | 436 | 438 | 440 |",
  "example": "/samd/news/440",
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
    "hualiong"
  ],
  "module": "() => import('@/routes/samd/news.ts')",
  "name": "资讯信息",
  "parameters": {
    "type": "文章类型ID，见下表"
  },
  "path": "/news/:typeId"
}
```
