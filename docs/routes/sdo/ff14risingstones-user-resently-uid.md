# 盛趣游戏在线 - 游戏近况

## Coverage
`index-only`

## Route
- Namespace: `sdo`
- Namespace Name: `盛趣游戏在线`
- Route Path: `/ff14risingstones/user-resently/:uid`
- Route Name: `游戏近况`
- Example: `/sdo/ff14risingstones/user-resently/10008214`
- URL: `sdo.com`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `KarasuShin`
- Source Location: `ff14risingstones/user-resently.ts`
- Source Module: `() => import('@/routes/sdo/ff14risingstones/user-resently.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: [{"description": "值为 Cookie 头中 ff14risingstones 值", "name": "SDO_FF14RISINGSTONES"}, {"description": "值为与在网页端获取 Cookie 时相匹配的 User-Agent 值", "name": "SDO_UA"}]

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/sdo/ff14risingstones/user-resently/10008214",
  "features": {
    "requireConfig": [
      {
        "description": "值为 Cookie 头中 ff14risingstones 值",
        "name": "SDO_FF14RISINGSTONES"
      },
      {
        "description": "值为与在网页端获取 Cookie 时相匹配的 User-Agent 值",
        "name": "SDO_UA"
      }
    ]
  },
  "location": "ff14risingstones/user-resently.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "module": "() => import('@/routes/sdo/ff14risingstones/user-resently.ts')",
  "name": "游戏近况",
  "path": "/ff14risingstones/user-resently/:uid"
}
```
