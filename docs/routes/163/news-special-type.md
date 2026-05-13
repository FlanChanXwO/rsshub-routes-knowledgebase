# 网易公开课 - 专栏

## Coverage
`index-only`

## Route
- Namespace: `163`
- Namespace Name: `网易公开课`
- Route Path: `/news/special/:type?`
- Route Name: `专栏`
- Example: `/163/news/special/1`
- URL: `163.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `news/special.ts`
- Source Module: `() => import('@/routes/163/news/special.ts')`

## Description
| 轻松一刻 | 槽值 | 人间 | 大国小民 | 三三有梗 | 数读 | 看客 | 下划线 | 谈心社 | 哒哒 | 胖编怪聊 | 曲一刀 | 今日之声 | 浪潮 | 沸点 |
| -------- | ---- | ---- | -------- | -------- | ---- | ---- | ------ | ------ | ---- | -------- | ------ | -------- | ---- | ---- |
| 1        | 2    | 3    | 4        | 5        | 6    | 7    | 8      | 9      | 10   | 11       | 12     | 13       | 14   | 15   |

## Parameters
- `type`: 栏目


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
  "description": "| 轻松一刻 | 槽值 | 人间 | 大国小民 | 三三有梗 | 数读 | 看客 | 下划线 | 谈心社 | 哒哒 | 胖编怪聊 | 曲一刀 | 今日之声 | 浪潮 | 沸点 |\n| -------- | ---- | ---- | -------- | -------- | ---- | ---- | ------ | ------ | ---- | -------- | ------ | -------- | ---- | ---- |\n| 1        | 2    | 3    | 4        | 5        | 6    | 7    | 8      | 9      | 10   | 11       | 12     | 13       | 14   | 15   |",
  "example": "/163/news/special/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news/special.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/163/news/special.ts')",
  "name": "专栏",
  "parameters": {
    "type": "栏目"
  },
  "path": "/news/special/:type?"
}
```
