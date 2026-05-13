# 中国科学院大学 - 招聘信息

## Coverage
`index-only`

## Route
- Namespace: `ucas`
- Namespace Name: `中国科学院大学`
- Route Path: `/job/:type?`
- Route Name: `招聘信息`
- Example: `/ucas/job`
- URL: `ai.ucas.ac.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `Fatpandac`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/ucas/index.ts')`

## Description
| 招聘类型 | 博士后 | 课题项目聘用 | 管理支撑人才 | 教学科研人才 |
| :------: | :----: | :----------: | :----------: | :----------: |
|   参数   |   bsh  |    ktxmpy    |    glzcrc    |    jxkyrc    |

## Parameters
- `type`: 招聘类型，默认为博士后


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
  "description": "| 招聘类型 | 博士后 | 课题项目聘用 | 管理支撑人才 | 教学科研人才 |\n| :------: | :----: | :----------: | :----------: | :----------: |\n|   参数   |   bsh  |    ktxmpy    |    glzcrc    |    jxkyrc    |",
  "example": "/ucas/job",
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
    "Fatpandac"
  ],
  "module": "() => import('@/routes/ucas/index.ts')",
  "name": "招聘信息",
  "parameters": {
    "type": "招聘类型，默认为博士后"
  },
  "path": "/job/:type?"
}
```
