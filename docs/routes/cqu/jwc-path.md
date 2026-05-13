# 重庆大学 - 本科教学信息网通知

## Coverage
`index-only`

## Route
- Namespace: `cqu`
- Namespace Name: `重庆大学`
- Route Path: `/jwc/:path{.+}?`
- Route Name: `本科教学信息网通知`
- Example: `/cqu/jwc/index/tzgg`
- URL: `cqu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `AhsokaTano26`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/cqu/index.ts')`

## Description
_None_

## Parameters
- `path`: {"default": "index/tzgg", "description": "路径参数，默认为 `index/tzgg`"}


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
  - `jwc.cqu.edu.cn/:path`
- `target`: `/jwc/:path`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/cqu/jwc/index/tzgg",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "AhsokaTano26"
  ],
  "module": "() => import('@/routes/cqu/index.ts')",
  "name": "本科教学信息网通知",
  "parameters": {
    "path": {
      "default": "index/tzgg",
      "description": "路径参数，默认为 `index/tzgg`"
    }
  },
  "path": "/jwc/:path{.+}?",
  "radar": [
    {
      "source": [
        "jwc.cqu.edu.cn/:path"
      ],
      "target": "/jwc/:path"
    }
  ]
}
```
