# 南开大学 - 通知公告

## Coverage
`index-only`

## Route
- Namespace: `nankai`
- Namespace Name: `南开大学`
- Route Path: `/notice`
- Route Name: `通知公告`
- Example: `/nankai/notice`
- URL: `yzb.nankai.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `vicguo0724`
- Source Location: `notice.ts`
- Source Module: `() => import('@/routes/nankai/notice.ts')`

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
  - `www.nankai.edu.cn`
  - `www.nankai.edu.cn/157/list.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/nankai/notice",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "notice.ts",
  "maintainers": [
    "vicguo0724"
  ],
  "module": "() => import('@/routes/nankai/notice.ts')",
  "name": "通知公告",
  "parameters": {},
  "path": "/notice",
  "radar": [
    {
      "source": [
        "www.nankai.edu.cn",
        "www.nankai.edu.cn/157/list.htm"
      ]
    }
  ]
}
```
