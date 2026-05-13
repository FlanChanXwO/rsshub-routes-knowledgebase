# 豆瓣 - 新书速递

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/book/latest/:type?`
- Route Name: `新书速递`
- Example: `/douban/book/latest/fiction`
- URL: `www.douban.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `fengkx, lyqluis`
- Source Location: `book/latest.ts`
- Source Module: `() => import('@/routes/douban/book/latest.ts')`

## Description
| 文学         | 小说    | 历史文化 | 社会纪实  | 科学新知 | 艺术设计 | 商业经管 | 绘本漫画 |
| ------------ | ------- | -------- | --------- | -------- | -------- | -------- | -------- |
| prose_poetry | fiction | history  | biography | science  | art      | business | comics   |

## Parameters
- `type`: 专题分类，可选，默认为 `all`


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
    "social-media"
  ],
  "description": "| 文学         | 小说    | 历史文化 | 社会纪实  | 科学新知 | 艺术设计 | 商业经管 | 绘本漫画 |\n| ------------ | ------- | -------- | --------- | -------- | -------- | -------- | -------- |\n| prose_poetry | fiction | history  | biography | science  | art      | business | comics   |",
  "example": "/douban/book/latest/fiction",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "book/latest.ts",
  "maintainers": [
    "fengkx",
    "lyqluis"
  ],
  "module": "() => import('@/routes/douban/book/latest.ts')",
  "name": "新书速递",
  "parameters": {
    "type": "专题分类，可选，默认为 `all`"
  },
  "path": "/book/latest/:type?"
}
```
