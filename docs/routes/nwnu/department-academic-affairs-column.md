# 西北师范大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `nwnu`
- Namespace Name: `西北师范大学`
- Route Path: `/department/academic-affairs/:column`
- Route Name: `教务处`
- Example: `/department/academic-affairs/tzgg`
- URL: `www.nwnu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `PrinOrange`
- Source Location: `routes/department/academic-affairs.ts`
- Source Module: `() => import('@/routes/nwnu/routes/department/academic-affairs.ts')`

## Description
| column | 标题     | 描述                     |
| ------ | -------- | ------------------------ |
| tzgg   | 通知公告 | 西北师范大学教务通知公告 |
| jwkx   | 教务快讯 | 西北师范大学教务快讯     |

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportRadar`: true
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `jwc.nwnu.edu.cn/:column/list.htm`
- `target`: `/department/academic-affairs/:column`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "\n| column | 标题     | 描述                     |\n| ------ | -------- | ------------------------ |\n| tzgg   | 通知公告 | 西北师范大学教务通知公告 |\n| jwkx   | 教务快讯 | 西北师范大学教务快讯     |",
  "example": "/department/academic-affairs/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "routes/department/academic-affairs.ts",
  "maintainers": [
    "PrinOrange"
  ],
  "module": "() => import('@/routes/nwnu/routes/department/academic-affairs.ts')",
  "name": "教务处",
  "path": "/department/academic-affairs/:column",
  "radar": [
    {
      "source": [
        "jwc.nwnu.edu.cn/:column/list.htm"
      ],
      "target": "/department/academic-affairs/:column"
    }
  ]
}
```
