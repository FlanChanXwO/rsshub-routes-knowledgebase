# 北京航空航天大学 - 新闻网

## Coverage
`index-only`

## Route
- Namespace: `buaa`
- Namespace Name: `北京航空航天大学`
- Route Path: `/news/:type`
- Route Name: `新闻网`
- Example: `/buaa/news/zhxw`
- URL: `news.buaa.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `AlanDecode`
- Source Location: `news/index.ts`
- Source Module: `() => import('@/routes/buaa/news/index.ts')`

## Description
| 综合新闻 | 信息公告 | 学术文化    | 校园风采 | 科教在线 | 媒体北航 | 专题新闻 | 北航人物 |
| -------- | -------- | ----------- | -------- | -------- | -------- | -------- | -------- |
| zhxw     | xxgg_new | xsjwhhd_new | xyfc_new | kjzx_new | mtbh_new | ztxw     | bhrw     |

## Parameters
- `type`: 新闻版块


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
  "description": "| 综合新闻 | 信息公告 | 学术文化    | 校园风采 | 科教在线 | 媒体北航 | 专题新闻 | 北航人物 |\n| -------- | -------- | ----------- | -------- | -------- | -------- | -------- | -------- |\n| zhxw     | xxgg_new | xsjwhhd_new | xyfc_new | kjzx_new | mtbh_new | ztxw     | bhrw     |",
  "example": "/buaa/news/zhxw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news/index.ts",
  "maintainers": [
    "AlanDecode"
  ],
  "module": "() => import('@/routes/buaa/news/index.ts')",
  "name": "新闻网",
  "parameters": {
    "type": "新闻版块"
  },
  "path": "/news/:type"
}
```
