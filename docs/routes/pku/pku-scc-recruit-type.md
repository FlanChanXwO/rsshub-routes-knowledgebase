# 北京大学 - 学生就业指导服务中心

## Coverage
`index-only`

## Route
- Namespace: `pku`
- Namespace Name: `北京大学`
- Route Path: `/pku/scc/recruit/:type?`
- Route Name: `学生就业指导服务中心`
- Example: `/pku/scc/recruit/zpxx`
- URL: `admission.pku.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `DylanXie123`
- Source Location: `scc/recruit.ts`
- Source Module: `_None_`

## Description
| xwrd     | tzgg     | zpxx     | sxxx     | cyxx     |
| -------- | -------- | -------- | -------- | -------- |
| 新闻热点 | 通知公告 | 招聘信息 | 实习信息 | 创业信息 |

## Parameters
- `type`: 分区，见下表，默认请求 `zpxx`


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
  "description": "| xwrd     | tzgg     | zpxx     | sxxx     | cyxx     |\n| -------- | -------- | -------- | -------- | -------- |\n| 新闻热点 | 通知公告 | 招聘信息 | 实习信息 | 创业信息 |",
  "example": "/pku/scc/recruit/zpxx",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "scc/recruit.ts",
  "maintainers": [
    "DylanXie123"
  ],
  "name": "学生就业指导服务中心",
  "parameters": {
    "type": "分区，见下表，默认请求 `zpxx`"
  },
  "path": "/scc/recruit/:type?",
  "topFeeds": []
}
```
