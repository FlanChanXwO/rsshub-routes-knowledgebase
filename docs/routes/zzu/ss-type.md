# 郑州大学 - 郑大社科院

## Coverage
`index-only`

## Route
- Namespace: `zzu`
- Namespace Name: `郑州大学`
- Route Path: `/ss/:type`
- Route Name: `郑大社科院`
- Example: `/zzu/ss/xwzx`
- URL: `www.zzu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `amandus1990`
- Source Location: `ss.ts`
- Source Module: `() => import('@/routes/zzu/ss.ts')`

## Description
| 新闻资讯 | 通知公告 |
| -------- | -------- |
| xwzx     | tzgg     |

## Parameters
- `type`: 分类名


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
  - `www5.zzu.edu.cn/ss/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 新闻资讯 | 通知公告 |\n| -------- | -------- |\n| xwzx     | tzgg     |",
  "example": "/zzu/ss/xwzx",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "ss.ts",
  "maintainers": [
    "amandus1990"
  ],
  "module": "() => import('@/routes/zzu/ss.ts')",
  "name": "郑大社科院",
  "parameters": {
    "type": "分类名"
  },
  "path": "/ss/:type",
  "radar": [
    {
      "source": [
        "www5.zzu.edu.cn/ss/"
      ]
    }
  ]
}
```
