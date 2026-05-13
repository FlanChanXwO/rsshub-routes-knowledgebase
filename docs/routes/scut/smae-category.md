# 华南理工大学 - 机械与汽车工程学院 - 通知公告

## Coverage
`index-only`

## Route
- Namespace: `scut`
- Namespace Name: `华南理工大学`
- Route Path: `/smae/:category?`
- Route Name: `机械与汽车工程学院 - 通知公告`
- Example: `/scut/smae/yjsjw`
- URL: `jw.scut.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `Ermaotie`
- Source Location: `smae/notice.ts`
- Source Module: `() => import('@/routes/scut/smae/notice.ts')`

## Description
| 公务信息 | 党建工作 | 人事工作 | 学生工作 | 科研实验室 | 本科生教务 | 研究生教务 |
| -------- | -------- | -------- | -------- | ---------- | ---------- | ---------- |
| gwxx     | djgz     | rsgz     | xsgz     | kysys      | bksjw      | yjsjw      |

## Parameters
- `category`: 通知分类，默认为 `yjsjw`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
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
  "description": "| 公务信息 | 党建工作 | 人事工作 | 学生工作 | 科研实验室 | 本科生教务 | 研究生教务 |\n| -------- | -------- | -------- | -------- | ---------- | ---------- | ---------- |\n| gwxx     | djgz     | rsgz     | xsgz     | kysys      | bksjw      | yjsjw      |",
  "example": "/scut/smae/yjsjw",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "smae/notice.ts",
  "maintainers": [
    "Ermaotie"
  ],
  "module": "() => import('@/routes/scut/smae/notice.ts')",
  "name": "机械与汽车工程学院 - 通知公告",
  "parameters": {
    "category": "通知分类，默认为 `yjsjw`"
  },
  "path": "/smae/:category?"
}
```
