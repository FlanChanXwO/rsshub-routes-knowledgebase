# 国家能源局 - 太原市人力资源和社会保障局政府公开信息

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/taiyuan/rsj/:caty/:page?`
- Route Name: `太原市人力资源和社会保障局政府公开信息`
- Example: `/gov/taiyuan/rsj/gggs`
- URL: `rsj.taiyuan.gov.cn/*`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `2PoL`
- Source Location: `taiyuan/rsj.ts`
- Source Module: `() => import('@/routes/gov/taiyuan/rsj.ts')`

## Description
| 工作动态 | 太原新闻 | 通知公告 | 县区动态 | 国内动态 | 图片新闻 |
| -------- | -------- | -------- | -------- | -------- | -------- |
| gzdt     | tyxw     | gggs     | xqdt     | gndt     | tpxw     |

## Parameters
- `caty`: 信息类别
- `page`: 页码


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
  - `rsj.taiyuan.gov.cn/*`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 工作动态 | 太原新闻 | 通知公告 | 县区动态 | 国内动态 | 图片新闻 |\n| -------- | -------- | -------- | -------- | -------- | -------- |\n| gzdt     | tyxw     | gggs     | xqdt     | gndt     | tpxw     |",
  "example": "/gov/taiyuan/rsj/gggs",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "taiyuan/rsj.ts",
  "maintainers": [
    "2PoL"
  ],
  "module": "() => import('@/routes/gov/taiyuan/rsj.ts')",
  "name": "太原市人力资源和社会保障局政府公开信息",
  "parameters": {
    "caty": "信息类别",
    "page": "页码"
  },
  "path": "/taiyuan/rsj/:caty/:page?",
  "radar": [
    {
      "source": [
        "rsj.taiyuan.gov.cn/*"
      ]
    }
  ],
  "url": "rsj.taiyuan.gov.cn/*"
}
```
