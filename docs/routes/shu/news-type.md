# 上海大学 - 官网通知公告

## Coverage
`index-only`

## Route
- Namespace: `shu`
- Namespace Name: `上海大学`
- Route Path: `/news/:type?`
- Route Name: `官网通知公告`
- Example: `/shu/news/tzgg`
- URL: `www.shu.edu.cn/`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `lonelyion, GhhG123`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/shu/index.ts')`

## Description
| 通知公告 | 重要新闻 |
| -------- | --------- |
| tzgg     | zyxw      |

## Parameters
- `type`: 分类，默认为通知公告


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
  - `www.shu.edu.cn/`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知公告 | 重要新闻 |\n| -------- | --------- |\n| tzgg     | zyxw      |",
  "example": "/shu/news/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "lonelyion",
    "GhhG123"
  ],
  "module": "() => import('@/routes/shu/index.ts')",
  "name": "官网通知公告",
  "parameters": {
    "type": "分类，默认为通知公告"
  },
  "path": "/news/:type?",
  "radar": [
    {
      "source": [
        "www.shu.edu.cn/"
      ],
      "target": "/news"
    }
  ],
  "url": "www.shu.edu.cn/"
}
```
