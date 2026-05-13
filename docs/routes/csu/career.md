# 中南大学 - 就业信息网招聘信息

## Coverage
`index-only`

## Route
- Namespace: `csu`
- Namespace Name: `中南大学`
- Route Path: `/career`
- Route Name: `就业信息网招聘信息`
- Example: `/csu/career`
- URL: `career.csu.edu.cn/campus/index/category/1`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `TonyRL`
- Source Location: `career.ts`
- Source Module: `() => import('@/routes/csu/career.ts')`

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
  - `career.csu.edu.cn/campus/index/category/1`
  - `career.csu.edu.cn/campus`
  - `career.csu.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/csu/career",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "career.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/csu/career.ts')",
  "name": "就业信息网招聘信息",
  "parameters": {},
  "path": "/career",
  "radar": [
    {
      "source": [
        "career.csu.edu.cn/campus/index/category/1",
        "career.csu.edu.cn/campus",
        "career.csu.edu.cn/"
      ]
    }
  ],
  "url": "career.csu.edu.cn/campus/index/category/1"
}
```
