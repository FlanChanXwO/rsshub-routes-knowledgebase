# 北京化工大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `buct`
- Namespace Name: `北京化工大学`
- Route Path: `/jwc`
- Route Name: `教务处`
- Example: `/buct/jwc`
- URL: `buct.edu.cn/`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `Epic-Creeper`
- Source Location: `jwc.ts`
- Source Module: `() => import('@/routes/buct/jwc.ts')`

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
  - `jiaowuchu.buct.edu.cn/610/list.htm`
  - `jiaowuchu.buct.edu.cn/611/main.htm`
- `target`: `/jwc`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/buct/jwc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jwc.ts",
  "maintainers": [
    "Epic-Creeper"
  ],
  "module": "() => import('@/routes/buct/jwc.ts')",
  "name": "教务处",
  "parameters": {},
  "path": "/jwc",
  "radar": [
    {
      "source": [
        "jiaowuchu.buct.edu.cn/610/list.htm",
        "jiaowuchu.buct.edu.cn/611/main.htm"
      ],
      "target": "/jwc"
    }
  ],
  "url": "buct.edu.cn/"
}
```
