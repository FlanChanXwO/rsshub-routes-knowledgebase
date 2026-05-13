# 联想 - 驱动

## Coverage
`index-only`

## Route
- Namespace: `lenovo`
- Namespace Name: `联想`
- Route Path: `/drive/:selName`
- Route Name: `驱动`
- Example: `/lenovo/drive/PF3WRD2G`
- URL: `lenovo.com.cn`
- Language: `zh-CN`
- Categories: `program-update`
- Maintainers: `cscnk52`
- Source Location: `drive.tsx`
- Source Module: `() => import('@/routes/lenovo/drive.tsx')`

## Description
_None_

## Parameters
- `selName`: 产品序列号


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
  - `lenovo.com.cn`
- `target`: `/drive/:selName`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/lenovo/drive/PF3WRD2G",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "drive.tsx",
  "maintainers": [
    "cscnk52"
  ],
  "module": "() => import('@/routes/lenovo/drive.tsx')",
  "name": "驱动",
  "parameters": {
    "selName": "产品序列号"
  },
  "path": "/drive/:selName",
  "radar": [
    {
      "source": [
        "lenovo.com.cn"
      ],
      "target": "/drive/:selName"
    }
  ]
}
```
