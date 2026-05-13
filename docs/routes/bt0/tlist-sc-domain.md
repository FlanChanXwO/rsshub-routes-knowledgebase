# 不太灵影视 - 最新资源列表

## Coverage
`index-only`

## Route
- Namespace: `bt0`
- Namespace Name: `不太灵影视`
- Route Path: `/tlist/:sc/:domain?`
- Route Name: `最新资源列表`
- Example: `/bt0/tlist/1`
- URL: `2bt0.com`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `miemieYaho`
- Source Location: `tlist.ts`
- Source Module: `() => import('@/routes/bt0/tlist.ts')`

## Description
_None_

## Parameters
- `sc`: 分类(1-5), 1:电影, 2:电视剧, 3:近日热门, 4:本周热门, 5:本月热门
- `domain`: 数字1-9, 比如1表示请求域名为 1bt0.com, 默认为 2


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: true
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `2bt0.com/tlist/`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/bt0/tlist/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": true,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "tlist.ts",
  "maintainers": [
    "miemieYaho"
  ],
  "module": "() => import('@/routes/bt0/tlist.ts')",
  "name": "最新资源列表",
  "parameters": {
    "domain": "数字1-9, 比如1表示请求域名为 1bt0.com, 默认为 2",
    "sc": "分类(1-5), 1:电影, 2:电视剧, 3:近日热门, 4:本周热门, 5:本月热门"
  },
  "path": "/tlist/:sc/:domain?",
  "radar": [
    {
      "source": [
        "2bt0.com/tlist/"
      ]
    }
  ]
}
```
