# 中国无线电协会业余无线电分会 - 最新资讯

## Coverage
`index-only`

## Route
- Namespace: `crac`
- Namespace Name: `中国无线电协会业余无线电分会`
- Route Path: `/:type?`
- Route Name: `最新资讯`
- Example: `/crac/2`
- URL: `www.crac.org.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `Misaka13514`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/crac/index.ts')`

## Description
| 新闻动态 | 通知公告 | 政策法规 | 常见问题 | 资料下载 | English | 业余中继台 | 科普专栏 |
| -------- | -------- | -------- | -------- | -------- | ------- | ---------- | -------- |
| 1        | 2        | 3        | 5        | 6        | 7       | 8          | 9        |

## Parameters
- `type`: 类型，见下表，默认为全部


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
  - `www.crac.org.cn/News/*`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 新闻动态 | 通知公告 | 政策法规 | 常见问题 | 资料下载 | English | 业余中继台 | 科普专栏 |\n| -------- | -------- | -------- | -------- | -------- | ------- | ---------- | -------- |\n| 1        | 2        | 3        | 5        | 6        | 7       | 8          | 9        |",
  "example": "/crac/2",
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
    "Misaka13514"
  ],
  "module": "() => import('@/routes/crac/index.ts')",
  "name": "最新资讯",
  "parameters": {
    "type": "类型，见下表，默认为全部"
  },
  "path": "/:type?",
  "radar": [
    {
      "source": [
        "www.crac.org.cn/News/*"
      ]
    }
  ]
}
```
