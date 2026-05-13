# 郑州大学 - 郑大教务部

## Coverage
`index-only`

## Route
- Namespace: `zzu`
- Namespace Name: `郑州大学`
- Route Path: `/jwc/:type`
- Route Name: `郑大教务部`
- Example: `/zzu/jwc/xwkd`
- URL: `www.zzu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `amandus1990`
- Source Location: `jwc.ts`
- Source Module: `() => import('@/routes/zzu/jwc.ts')`

## Description
| 新闻快递 | 通知公告 |
| -------- | -------- |
| xwkd     | tzgg     |

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
  - `www5.zzu.edu.cn/jwc/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 新闻快递 | 通知公告 |\n| -------- | -------- |\n| xwkd     | tzgg     |",
  "example": "/zzu/jwc/xwkd",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jwc.ts",
  "maintainers": [
    "amandus1990"
  ],
  "module": "() => import('@/routes/zzu/jwc.ts')",
  "name": "郑大教务部",
  "parameters": {
    "type": "分类名"
  },
  "path": "/jwc/:type",
  "radar": [
    {
      "source": [
        "www5.zzu.edu.cn/jwc/"
      ]
    }
  ]
}
```
