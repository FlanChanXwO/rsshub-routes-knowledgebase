# 懂球帝 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `dongqiudi`
- Namespace Name: `懂球帝`
- Route Path: `/top_news/:id?`
- Route Name: `新闻`
- Example: `/dongqiudi/top_news/1`
- URL: `m.dongqiudi.com`
- Language: `zh-CN`
- Categories: `sport`
- Maintainers: `HendricksZheng`
- Source Location: `top-news.ts`
- Source Module: `() => import('@/routes/dongqiudi/top-news.ts')`

## Description
| 头条 | 深度 | 闲情 | D 站 | 中超 | 国际 | 英超 | 西甲 | 意甲 | 德甲 |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| 1    | 55   | 37   | 219  | 56   | 120  | 3    | 5    | 4    | 6    |

## Parameters
- `id`: 类别 id，不填默认头条新闻


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `m.dongqiudi.com/home/:id`
- `target`: `/top_news/:id`

## Raw JSON
```json
{
  "categories": [
    "sport"
  ],
  "description": "| 头条 | 深度 | 闲情 | D 站 | 中超 | 国际 | 英超 | 西甲 | 意甲 | 德甲 |\n| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |\n| 1    | 55   | 37   | 219  | 56   | 120  | 3    | 5    | 4    | 6    |",
  "example": "/dongqiudi/top_news/1",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "top-news.ts",
  "maintainers": [
    "HendricksZheng"
  ],
  "module": "() => import('@/routes/dongqiudi/top-news.ts')",
  "name": "新闻",
  "parameters": {
    "id": "类别 id，不填默认头条新闻"
  },
  "path": "/top_news/:id?",
  "radar": [
    {
      "source": [
        "m.dongqiudi.com/home/:id"
      ],
      "target": "/top_news/:id"
    }
  ]
}
```
