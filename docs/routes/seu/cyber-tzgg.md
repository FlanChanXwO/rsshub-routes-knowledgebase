# 东南大学 - 网络空间安全学院 - 通知公告

## Coverage
`index-only`

## Route
- Namespace: `seu`
- Namespace Name: `东南大学`
- Route Path: `/cyber/tzgg`
- Route Name: `网络空间安全学院 - 通知公告`
- Example: `/seu/cyber/tzgg`
- URL: `cse.seu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `shrugginG`
- Source Location: `cyber/index.ts`
- Source Module: `() => import('@/routes/seu/cyber/index.ts')`

## Description
东南大学网络空间安全学院通知公告

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
  - `cyber.seu.edu.cn/tzgg/list.htm`
  - `cyber.seu.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "东南大学网络空间安全学院通知公告",
  "example": "/seu/cyber/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "cyber/index.ts",
  "maintainers": [
    "shrugginG"
  ],
  "module": "() => import('@/routes/seu/cyber/index.ts')",
  "name": "网络空间安全学院 - 通知公告",
  "parameters": {},
  "path": "/cyber/tzgg",
  "radar": [
    {
      "source": [
        "cyber.seu.edu.cn/tzgg/list.htm",
        "cyber.seu.edu.cn/"
      ]
    }
  ]
}
```
