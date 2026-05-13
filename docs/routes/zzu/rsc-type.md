# 郑州大学 - 郑大人事部

## Coverage
`index-only`

## Route
- Namespace: `zzu`
- Namespace Name: `郑州大学`
- Route Path: `/rsc/:type`
- Route Name: `郑大人事部`
- Example: `/zzu/rsc/rsyw`
- URL: `www.zzu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `amandus1990`
- Source Location: `rsc.ts`
- Source Module: `() => import('@/routes/zzu/rsc.ts')`

## Description
| 人事要闻 | 通知公告 | 招聘公告 |
| -------- | -------- | -------- |
| rsyw     | tzgg     | zpxx     |

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
  - `www5.zzu.edu.cn/rsc/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 人事要闻 | 通知公告 | 招聘公告 |\n| -------- | -------- | -------- |\n| rsyw     | tzgg     | zpxx     |",
  "example": "/zzu/rsc/rsyw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "rsc.ts",
  "maintainers": [
    "amandus1990"
  ],
  "module": "() => import('@/routes/zzu/rsc.ts')",
  "name": "郑大人事部",
  "parameters": {
    "type": "分类名"
  },
  "path": "/rsc/:type",
  "radar": [
    {
      "source": [
        "www5.zzu.edu.cn/rsc/"
      ]
    }
  ]
}
```
