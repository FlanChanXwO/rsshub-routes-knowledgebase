# 山东大学 - 新闻网

## Coverage
`index-only`

## Route
- Namespace: `sdu`
- Namespace Name: `山东大学`
- Route Path: `/sdu/wh/news/:column?`
- Route Name: `新闻网`
- Example: `/sdu/wh/news/xyyw`
- URL: `www.sdu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `kxxt`
- Source Location: `wh/news.ts`
- Source Module: `_None_`

## Description
| 校园要闻 | 学生动态 | 综合新闻 | 山大视点 | 菁菁校园 | 校园简讯 | 玛珈之窗 | 热点专题 | 媒体视角 | 高教视野 | 理论学习 |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| xyyw     | xsdt     | zhxw     | sdsd     | jjxy     | xyjx     | mjzc     | rdzt     | mtsj     | gjsy     | llxx     |

## Parameters
- `column`: 专栏名称，默认为校园要闻（`xyyw`）


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 校园要闻 | 学生动态 | 综合新闻 | 山大视点 | 菁菁校园 | 校园简讯 | 玛珈之窗 | 热点专题 | 媒体视角 | 高教视野 | 理论学习 |\n| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |\n| xyyw     | xsdt     | zhxw     | sdsd     | jjxy     | xyjx     | mjzc     | rdzt     | mtsj     | gjsy     | llxx     |",
  "example": "/sdu/wh/news/xyyw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "wh/news.ts",
  "maintainers": [
    "kxxt"
  ],
  "name": "新闻网",
  "parameters": {
    "column": "专栏名称，默认为校园要闻（`xyyw`）"
  },
  "path": "/wh/news/:column?",
  "topFeeds": []
}
```
