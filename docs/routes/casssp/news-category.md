# 中国科学学与科技政策研究会 - 研究会动态

## Coverage
`index-only`

## Route
- Namespace: `casssp`
- Namespace Name: `中国科学学与科技政策研究会`
- Route Path: `/news/:category?`
- Route Name: `研究会动态`
- Example: `/casssp/news/3`
- URL: `casssp.org.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/casssp/news.ts')`

## Description
| 通知公告 | 新闻动态 | 信息公开 | 时政要闻 |
| -------- | -------- | -------- | -------- |
| 3        | 2        | 92       | 93       |

## Parameters
- `category`: 分类，见下表，默认为通知公告


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
  "description": "| 通知公告 | 新闻动态 | 信息公开 | 时政要闻 |\n| -------- | -------- | -------- | -------- |\n| 3        | 2        | 92       | 93       |",
  "example": "/casssp/news/3",
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
  "module": "() => import('@/routes/casssp/news.ts')",
  "name": "研究会动态",
  "parameters": {
    "category": "分类，见下表，默认为通知公告"
  },
  "path": "/news/:category?"
}
```
