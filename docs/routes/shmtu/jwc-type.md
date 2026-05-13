# 上海海事大学 - 教务信息

## Coverage
`index-only`

## Route
- Namespace: `shmtu`
- Namespace Name: `上海海事大学`
- Route Path: `/jwc/:type`
- Route Name: `教务信息`
- Example: `/shmtu/jwc/jwgg`
- URL: `jwc.shmtu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `imbytecat, simonsmh`
- Source Location: `jwc.ts`
- Source Module: `() => import('@/routes/shmtu/jwc.ts')`

## Description
| 教务公告 | 教务新闻 |
| -------- | -------- |
| jwgg     | jwxw     |

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
  - `jwc.shmtu.edu.cn/:type`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 教务公告 | 教务新闻 |\n| -------- | -------- |\n| jwgg     | jwxw     |",
  "example": "/shmtu/jwc/jwgg",
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
    "imbytecat",
    "simonsmh"
  ],
  "module": "() => import('@/routes/shmtu/jwc.ts')",
  "name": "教务信息",
  "parameters": {
    "type": "类型名称"
  },
  "path": "/jwc/:type",
  "radar": [
    {
      "source": [
        "jwc.shmtu.edu.cn/:type"
      ]
    }
  ]
}
```
