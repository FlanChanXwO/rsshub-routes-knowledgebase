# Hangzhou People's Government - 太原市人力资源和社会保障局政府公开信息

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `Hangzhou People's Government`
- Route Path: `/gov/taiyuan/rsj/:caty/:page?`
- Route Name: `太原市人力资源和社会保障局政府公开信息`
- Example: `/gov/taiyuan/rsj/gggs`
- URL: `rsj.taiyuan.gov.cn/*`
- Language: `_None_`
- Categories: `government`
- Maintainers: `2PoL`
- Source Location: `taiyuan/rsj.ts`
- Source Module: `_None_`

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
  "heat": 0,
  "location": "taiyuan/rsj.ts",
  "maintainers": [
    "2PoL"
  ],
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
  "topFeeds": [],
  "url": "rsj.taiyuan.gov.cn/*"
}
```
