# 西安交通大学 - 就业创业中心

## Coverage
`index-only`

## Route
- Namespace: `xjtu`
- Namespace Name: `西安交通大学`
- Route Path: `/job/:subpath?`
- Route Name: `就业创业中心`
- Example: `/xjtu/job/zxgg`
- URL: `2yuan.xjtu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `DylanXie123`
- Source Location: `job.tsx`
- Source Module: `() => import('@/routes/xjtu/job.tsx')`

## Description
栏目类型

| 中心公告 | 选调生 | 重点单位 | 国际组织 | 创新创业 | 就业实习 |
| -------- | ------ | -------- | -------- | -------- | -------- |
| zxgg     | xds    | zddw     | gjzz     | cxcy     | jysx     |

## Parameters
- `subpath`: 栏目类型，默认请求`zxgg`，详见下方表格


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
  "description": "栏目类型\n\n| 中心公告 | 选调生 | 重点单位 | 国际组织 | 创新创业 | 就业实习 |\n| -------- | ------ | -------- | -------- | -------- | -------- |\n| zxgg     | xds    | zddw     | gjzz     | cxcy     | jysx     |",
  "example": "/xjtu/job/zxgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "job.tsx",
  "maintainers": [
    "DylanXie123"
  ],
  "module": "() => import('@/routes/xjtu/job.tsx')",
  "name": "就业创业中心",
  "parameters": {
    "subpath": "栏目类型，默认请求`zxgg`，详见下方表格"
  },
  "path": "/job/:subpath?"
}
```
