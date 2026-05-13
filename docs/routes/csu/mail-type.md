# 中南大学 - 校长信箱

## Coverage
`index-only`

## Route
- Namespace: `csu`
- Namespace Name: `中南大学`
- Route Path: `/mail/:type?`
- Route Name: `校长信箱`
- Example: `/csu/mail`
- URL: `career.csu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `j1g5awi`
- Source Location: `mail.ts`
- Source Module: `() => import('@/routes/csu/mail.ts')`

## Description
| 类型 | 校长信箱 | 党委信箱 |
| ---- | -------- | -------- |
| 参数 | 01       | 02       |

## Parameters
- `type`: 类型


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
  "description": "| 类型 | 校长信箱 | 党委信箱 |\n| ---- | -------- | -------- |\n| 参数 | 01       | 02       |",
  "example": "/csu/mail",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "mail.ts",
  "maintainers": [
    "j1g5awi"
  ],
  "module": "() => import('@/routes/csu/mail.ts')",
  "name": "校长信箱",
  "parameters": {
    "type": "类型"
  },
  "path": "/mail/:type?"
}
```
