# 上海海事大学 - 数字平台

## Coverage
`index-only`

## Route
- Namespace: `shmtu`
- Namespace Name: `上海海事大学`
- Route Path: `/portal/:type`
- Route Name: `数字平台`
- Example: `/shmtu/portal/bmtzgg`
- URL: `jwc.shmtu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `imbytecat`
- Source Location: `portal.tsx`
- Source Module: `() => import('@/routes/shmtu/portal.tsx')`

## Description
| 部门通知公告 | 学术与大型活动公告 | 部门动态 |
| ------------ | ------------------ | -------- |
| bmtzgg       | xsydxhdgg          | bmdt     |

## Parameters
- `type`: 类型名称


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
  - `portal.shmtu.edu.cn/:type`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 部门通知公告 | 学术与大型活动公告 | 部门动态 |\n| ------------ | ------------------ | -------- |\n| bmtzgg       | xsydxhdgg          | bmdt     |",
  "example": "/shmtu/portal/bmtzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "portal.tsx",
  "maintainers": [
    "imbytecat"
  ],
  "module": "() => import('@/routes/shmtu/portal.tsx')",
  "name": "数字平台",
  "parameters": {
    "type": "类型名称"
  },
  "path": "/portal/:type",
  "radar": [
    {
      "source": [
        "portal.shmtu.edu.cn/:type"
      ]
    }
  ]
}
```
