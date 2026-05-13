# 山东大学 - 国际事务部

## Coverage
`index-only`

## Route
- Namespace: `sdu`
- Namespace Name: `山东大学`
- Route Path: `/gjsw/:type?`
- Route Name: `国际事务部`
- Example: `/sdu/gjsw/tzgg`
- URL: `www.sdu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `kukeya`
- Source Location: `gjsw.ts`
- Source Module: `() => import('@/routes/sdu/gjsw.ts')`

## Description
| 通知公告 |  
| -------- | 
| tzgg     |

## Parameters
- `type`: 默认为`tzgg`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知公告 |  \n| -------- | \n| tzgg     |      ",
  "example": "/sdu/gjsw/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "gjsw.ts",
  "maintainers": [
    "kukeya"
  ],
  "module": "() => import('@/routes/sdu/gjsw.ts')",
  "name": "国际事务部",
  "parameters": {
    "type": "默认为`tzgg`"
  },
  "path": "/gjsw/:type?"
}
```
