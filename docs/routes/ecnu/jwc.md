# East China Normal University 华东师范大学 - 教务处通知

## Coverage
`index-only`

## Route
- Namespace: `ecnu`
- Namespace Name: `East China Normal University 华东师范大学`
- Route Path: `/jwc`
- Route Name: `教务处通知`
- Example: `/ecnu/jwc`
- URL: `www.ecnu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `markbang`
- Source Location: `jwc.ts`
- Source Module: `() => import('@/routes/ecnu/jwc.ts')`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.jwc.ecnu.edu.cn`
- `target`: `/tzgg`
### Rule 2
- `source`:
  - `www.ecnu.edu.cn`
- `target`: `/tzgg`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/ecnu/jwc",
  "location": "jwc.ts",
  "maintainers": [
    "markbang"
  ],
  "module": "() => import('@/routes/ecnu/jwc.ts')",
  "name": "教务处通知",
  "path": "/jwc",
  "radar": [
    {
      "source": [
        "www.jwc.ecnu.edu.cn"
      ],
      "target": "/tzgg"
    },
    {
      "source": [
        "www.ecnu.edu.cn"
      ],
      "target": "/tzgg"
    }
  ]
}
```
