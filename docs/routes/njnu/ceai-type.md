# 南京师范大学 - 计算机与电子信息学院 - 人工智能学院

## Coverage
`index-only`

## Route
- Namespace: `njnu`
- Namespace Name: `南京师范大学`
- Route Path: `/ceai/:type`
- Route Name: `计算机与电子信息学院 - 人工智能学院`
- Example: `/njnu/ceai/xszx`
- URL: `ceai.njnu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `Shujakuinkuraudo`
- Source Location: `ceai/ceai.ts`
- Source Module: `() => import('@/routes/njnu/ceai/ceai.ts')`

## Description
| 学院公告 | 学院新闻 | 学生资讯 |
| -------- | -------- | -------- |
| xygg     | xyxw     | xszx     |

## Parameters
- `type`: 分类名


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
  "description": "| 学院公告 | 学院新闻 | 学生资讯 |\n| -------- | -------- | -------- |\n| xygg     | xyxw     | xszx     |",
  "example": "/njnu/ceai/xszx",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "ceai/ceai.ts",
  "maintainers": [
    "Shujakuinkuraudo"
  ],
  "module": "() => import('@/routes/njnu/ceai/ceai.ts')",
  "name": "计算机与电子信息学院 - 人工智能学院",
  "parameters": {
    "type": "分类名"
  },
  "path": "/ceai/:type"
}
```
