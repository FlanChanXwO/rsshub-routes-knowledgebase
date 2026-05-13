# 聯合新聞網 - 即時新聞

## Coverage
`index-only`

## Route
- Namespace: `udn`
- Namespace Name: `聯合新聞網`
- Route Path: `/news/breakingnews/:id`
- Route Name: `即時新聞`
- Example: `/udn/news/breakingnews/99`
- URL: `udn.com`
- Language: `zh-TW`
- Categories: `traditional-media`
- Maintainers: `miles170, pseudoyu`
- Source Location: `breaking-news.tsx`
- Source Module: `() => import('@/routes/udn/breaking-news.tsx')`

## Description
| 0    | 1    | 2    | 3    | 4    | 5    | 6    | 7    | 8    | 9    | 11   | 12   | 13   | 99     |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ------ |
| 精選 | 要聞 | 社會 | 地方 | 兩岸 | 國際 | 財經 | 運動 | 娛樂 | 生活 | 股市 | 文教 | 數位 | 不分類 |

## Parameters
- `id`: 类别


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `udn.com/news/breaknews/1/:id`
  - `udn.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 0    | 1    | 2    | 3    | 4    | 5    | 6    | 7    | 8    | 9    | 11   | 12   | 13   | 99     |\n| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ------ |\n| 精選 | 要聞 | 社會 | 地方 | 兩岸 | 國際 | 財經 | 運動 | 娛樂 | 生活 | 股市 | 文教 | 數位 | 不分類 |",
  "example": "/udn/news/breakingnews/99",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "breaking-news.tsx",
  "maintainers": [
    "miles170",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/udn/breaking-news.tsx')",
  "name": "即時新聞",
  "parameters": {
    "id": "类别"
  },
  "path": "/news/breakingnews/:id",
  "radar": [
    {
      "source": [
        "udn.com/news/breaknews/1/:id",
        "udn.com/"
      ]
    }
  ]
}
```
