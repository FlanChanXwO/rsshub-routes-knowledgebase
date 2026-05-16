# 南京航空航天大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `nuaa`
- Namespace Name: `南京航空航天大学`
- Route Path: `/nuaa/jwc/:type/:getDescription?`
- Route Name: `教务处`
- Example: `/nuaa/jwc/tzgg/getDescription`
- URL: `aao.nuaa.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `arcosx, Seiry, qrzbing, Xm798`
- Source Location: `jwc/jwc.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 教学服务 | 教学建设 | 学生培养 | 教学资源 |
| -------- | -------- | -------- | -------- | -------- |
| tzgg     | jxfw     | jxjs     | xspy     | jxzy     |

## Parameters
- `type`: 分类名，见下表
- `getDescription`: 是否获取全文


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
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
  "description": "| 通知公告 | 教学服务 | 教学建设 | 学生培养 | 教学资源 |\n| -------- | -------- | -------- | -------- | -------- |\n| tzgg     | jxfw     | jxjs     | xspy     | jxzy     |",
  "example": "/nuaa/jwc/tzgg/getDescription",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "jwc/jwc.ts",
  "maintainers": [
    "arcosx",
    "Seiry",
    "qrzbing",
    "Xm798"
  ],
  "name": "教务处",
  "parameters": {
    "getDescription": "是否获取全文",
    "type": "分类名，见下表"
  },
  "path": "/jwc/:type/:getDescription?",
  "topFeeds": []
}
```
