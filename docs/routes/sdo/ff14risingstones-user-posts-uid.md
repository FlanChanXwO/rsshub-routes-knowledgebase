# 盛趣游戏在线 - 用户发帖

## Coverage
`index-only`

## Route
- Namespace: `sdo`
- Namespace Name: `盛趣游戏在线`
- Route Path: `/ff14risingstones/user-posts/:uid`
- Route Name: `用户发帖`
- Example: `/sdo/ff14risingstones/user-posts/10001226`
- URL: `sdo.com`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `KarasuShin`
- Source Location: `ff14risingstones/user-posts.ts`
- Source Module: `() => import('@/routes/sdo/ff14risingstones/user-posts.ts')`

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
  "example": "/sdo/ff14risingstones/user-posts/10001226",
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
  "location": "ff14risingstones/user-posts.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "module": "() => import('@/routes/sdo/ff14risingstones/user-posts.ts')",
  "name": "用户发帖",
  "path": "/ff14risingstones/user-posts/:uid"
}
```
