# 电子科技大学 - 新闻中心

## Coverage
`index-only`

## Route
- Namespace: `uestc`
- Namespace Name: `电子科技大学`
- Route Path: `/news/:type?`
- Route Name: `新闻中心`
- Example: `/uestc/news/culture`
- URL: `news.uestc.edu.cn/`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `achjqz, mobyw`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/uestc/news.ts')`

## Description
| 学术    | 文化    | 公告         | 校内通知     |
| ------- | ------- | ------------ | ------------ |
| academy | culture | announcement | notification |

## Parameters
- `type`: 默认为 `announcement`


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
  - `news.uestc.edu.cn/`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 学术    | 文化    | 公告         | 校内通知     |\n| ------- | ------- | ------------ | ------------ |\n| academy | culture | announcement | notification |",
  "example": "/uestc/news/culture",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "achjqz",
    "mobyw"
  ],
  "module": "() => import('@/routes/uestc/news.ts')",
  "name": "新闻中心",
  "parameters": {
    "type": "默认为 `announcement`"
  },
  "path": "/news/:type?",
  "radar": [
    {
      "source": [
        "news.uestc.edu.cn/"
      ],
      "target": "/news"
    }
  ],
  "url": "news.uestc.edu.cn/"
}
```
