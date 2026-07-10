# 南京航空航天大学 - 计算机科学与技术学院

## Coverage
`index-only`

## Route
- Namespace: `nuaa`
- Namespace Name: `南京航空航天大学`
- Route Path: `/nuaa/cs/:type/:getDescription?`
- Route Name: `计算机科学与技术学院`
- Example: `/nuaa/cs/jxdt`
- URL: `aao.nuaa.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `LogicJake, Seiry, qrzbing, Xm798`
- Source Location: `college/cs.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 热点新闻 | 学科科研 | 教学动态 | 本科生培养 | 研究生培养 | 学生工作 |
| -------- | -------- | -------- | -------- | ---------- | ---------- | -------- |
| tzgg     | rdxw     | xkky     | jxdt     | be         | me         | xsgz     |

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
  "description": "| 通知公告 | 热点新闻 | 学科科研 | 教学动态 | 本科生培养 | 研究生培养 | 学生工作 |\n| -------- | -------- | -------- | -------- | ---------- | ---------- | -------- |\n| tzgg     | rdxw     | xkky     | jxdt     | be         | me         | xsgz     |",
  "example": "/nuaa/cs/jxdt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "college/cs.ts",
  "maintainers": [
    "LogicJake",
    "Seiry",
    "qrzbing",
    "Xm798"
  ],
  "name": "计算机科学与技术学院",
  "parameters": {
    "getDescription": "是否获取全文",
    "type": "分类名，见下表"
  },
  "path": "/cs/:type/:getDescription?",
  "topFeeds": []
}
```
