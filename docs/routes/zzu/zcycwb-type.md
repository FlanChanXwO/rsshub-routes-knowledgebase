# 郑州大学 - 郑大资产与财务部

## Coverage
`index-only`

## Route
- Namespace: `zzu`
- Namespace Name: `郑州大学`
- Route Path: `/zcycwb/:type`
- Route Name: `郑大资产与财务部`
- Example: `/zzu/zcycwb/xwzx`
- URL: `www.zzu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `amandus1990`
- Source Location: `zcycwb.ts`
- Source Module: `() => import('@/routes/zzu/zcycwb.ts')`

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
  - `www5.zzu.edu.cn/zcycwb/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 新闻资讯 | 通知公告 |\n| -------- | -------- |\n| xwzx     | tzgg     |",
  "example": "/zzu/zcycwb/xwzx",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "zcycwb.ts",
  "maintainers": [
    "amandus1990"
  ],
  "module": "() => import('@/routes/zzu/zcycwb.ts')",
  "name": "郑大资产与财务部",
  "parameters": {
    "type": "分类名"
  },
  "path": "/zcycwb/:type",
  "radar": [
    {
      "source": [
        "www5.zzu.edu.cn/zcycwb/"
      ]
    }
  ]
}
```
