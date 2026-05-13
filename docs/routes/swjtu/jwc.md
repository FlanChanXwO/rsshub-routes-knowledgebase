# 西南交通大学 - 教务网

## Coverage
`index-only`

## Route
- Namespace: `swjtu`
- Namespace Name: `西南交通大学`
- Route Path: `/jwc`
- Route Name: `教务网`
- Example: `/swjtu/jwc`
- URL: `jwc.swjtu.edu.cn/vatuu/WebAction`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `mobyw`
- Source Location: `jwc.ts`
- Source Module: `() => import('@/routes/swjtu/jwc.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `jwc.swjtu.edu.cn/vatuu/WebAction`
  - `jwc.swjtu.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/swjtu/jwc",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jwc.ts",
  "maintainers": [
    "mobyw"
  ],
  "module": "() => import('@/routes/swjtu/jwc.ts')",
  "name": "教务网",
  "parameters": {},
  "path": "/jwc",
  "radar": [
    {
      "source": [
        "jwc.swjtu.edu.cn/vatuu/WebAction",
        "jwc.swjtu.edu.cn/"
      ]
    }
  ],
  "url": "jwc.swjtu.edu.cn/vatuu/WebAction"
}
```
