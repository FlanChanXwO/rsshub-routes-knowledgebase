# 中国无线电协会业余无线电分会 - 考试信息

## Coverage
`index-only`

## Route
- Namespace: `crac`
- Namespace Name: `中国无线电协会业余无线电分会`
- Route Path: `/exam`
- Route Name: `考试信息`
- Example: `/crac/exam`
- URL: `www.crac.org.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `admxj`
- Source Location: `exam.tsx`
- Source Module: `() => import('@/routes/crac/exam.tsx')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.crac.org.cn/*`
- `target`: `/exam`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/crac/exam",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "exam.tsx",
  "maintainers": [
    "admxj"
  ],
  "module": "() => import('@/routes/crac/exam.tsx')",
  "name": "考试信息",
  "path": "/exam",
  "radar": [
    {
      "source": [
        "www.crac.org.cn/*"
      ],
      "target": "/exam"
    }
  ]
}
```
