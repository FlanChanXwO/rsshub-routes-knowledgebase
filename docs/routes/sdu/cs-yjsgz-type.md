# 山东大学 - 计算机科学与技术学院研究生工作网站

## Coverage
`index-only`

## Route
- Namespace: `sdu`
- Namespace Name: `山东大学`
- Route Path: `/cs/yjsgz/:type?`
- Route Name: `计算机科学与技术学院研究生工作网站`
- Example: `/sdu/cs/yjsgz/zytz`
- URL: `www.sdu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `kukeya, wiketool`
- Source Location: `cs/yjsgz.ts`
- Source Module: `() => import('@/routes/sdu/cs/yjsgz.ts')`

## Description
| 重要通知 | 公示栏 |
| -------- | -------- |
| zytz      | gsl       |

## Parameters
- `type`: 默认为`zytz`


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
  "description": "| 重要通知 | 公示栏 |\n| -------- | -------- |\n| zytz      | gsl       |",
  "example": "/sdu/cs/yjsgz/zytz",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "cs/yjsgz.ts",
  "maintainers": [
    "kukeya",
    "wiketool"
  ],
  "module": "() => import('@/routes/sdu/cs/yjsgz.ts')",
  "name": "计算机科学与技术学院研究生工作网站",
  "parameters": {
    "type": "默认为`zytz`"
  },
  "path": "/cs/yjsgz/:type?"
}
```
