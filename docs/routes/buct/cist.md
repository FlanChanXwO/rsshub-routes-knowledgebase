# 北京化工大学 - 信息学院

## Coverage
`index-only`

## Route
- Namespace: `buct`
- Namespace Name: `北京化工大学`
- Route Path: `/cist`
- Route Name: `信息学院`
- Example: `/buct/cist`
- URL: `buct.edu.cn/`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `Epic-Creeper`
- Source Location: `cist.ts`
- Source Module: `() => import('@/routes/buct/cist.ts')`

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
  - `cist.buct.edu.cn/xygg/list.htm`
  - `cist.buct.edu.cn/xygg/main.htm`
- `target`: `/cist`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/buct/cist",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "cist.ts",
  "maintainers": [
    "Epic-Creeper"
  ],
  "module": "() => import('@/routes/buct/cist.ts')",
  "name": "信息学院",
  "parameters": {},
  "path": "/cist",
  "radar": [
    {
      "source": [
        "cist.buct.edu.cn/xygg/list.htm",
        "cist.buct.edu.cn/xygg/main.htm"
      ],
      "target": "/cist"
    }
  ],
  "url": "buct.edu.cn/"
}
```
