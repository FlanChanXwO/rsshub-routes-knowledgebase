# 蓝桥云课 - 全站发布的课程

## Coverage
`index-only`

## Route
- Namespace: `lanqiao`
- Namespace Name: `蓝桥云课`
- Route Path: `/courses/:sort/:tag`
- Route Name: `全站发布的课程`
- Example: `/lanqiao/courses/latest/all`
- URL: `lanqiao.cn`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `huhuhang`
- Source Location: `courses.ts`
- Source Module: `() => import('@/routes/lanqiao/courses.ts')`

## Description
_None_

## Parameters
- `sort`: 排序规则 sort, 默认(`default`)、最新(`latest`)、最热(`hotest`)
- `tag`: 课程标签 `tag`，可在该页面找到：https://www.lanqiao.cn/courses/


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
    "programming"
  ],
  "example": "/lanqiao/courses/latest/all",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "courses.ts",
  "maintainers": [
    "huhuhang"
  ],
  "module": "() => import('@/routes/lanqiao/courses.ts')",
  "name": "全站发布的课程",
  "parameters": {
    "sort": "排序规则 sort, 默认(`default`)、最新(`latest`)、最热(`hotest`)",
    "tag": "课程标签 `tag`，可在该页面找到：https://www.lanqiao.cn/courses/"
  },
  "path": "/courses/:sort/:tag"
}
```
