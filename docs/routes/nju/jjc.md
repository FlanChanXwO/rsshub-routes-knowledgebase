# 南京大学 - 基建处

## Coverage
`index-only`

## Route
- Namespace: `nju`
- Namespace Name: `南京大学`
- Route Path: `/jjc`
- Route Name: `基建处`
- Example: `/nju/jjc`
- URL: `jjc.nju.edu.cn/main.htm`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `ret-1`
- Source Location: `jjc.ts`
- Source Module: `() => import('@/routes/nju/jjc.ts')`

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
  - `jjc.nju.edu.cn/main.htm`
  - `jjc.nju.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/nju/jjc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jjc.ts",
  "maintainers": [
    "ret-1"
  ],
  "module": "() => import('@/routes/nju/jjc.ts')",
  "name": "基建处",
  "parameters": {},
  "path": "/jjc",
  "radar": [
    {
      "source": [
        "jjc.nju.edu.cn/main.htm",
        "jjc.nju.edu.cn/"
      ]
    }
  ],
  "url": "jjc.nju.edu.cn/main.htm"
}
```
