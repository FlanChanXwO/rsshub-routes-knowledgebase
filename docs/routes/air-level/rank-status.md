# Air-Level - 空气质量排行

## Coverage
`index-only`

## Route
- Namespace: `air-level`
- Namespace Name: `Air-Level`
- Route Path: `/rank/:status?`
- Route Name: `空气质量排行`
- Example: `/air-level/rank/best,/air-level/rank`
- URL: `air-level.com`
- Language: `zh-CN`
- Categories: `forecast`
- Maintainers: `lifetraveler`
- Source Location: `levelrank.ts`
- Source Module: `() => import('@/routes/air-level/levelrank.ts')`

## Description
_None_

## Parameters
- `status`: 地区


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `m.air-level.com/rank/:status`
  - `m.air-level.com/rank`
- `target`: `/rank/:status`

## Raw JSON
```json
{
  "example": "/air-level/rank/best,/air-level/rank",
  "location": "levelrank.ts",
  "maintainers": [
    "lifetraveler"
  ],
  "module": "() => import('@/routes/air-level/levelrank.ts')",
  "name": "空气质量排行",
  "parameters": {
    "status": "地区"
  },
  "path": [
    "/rank/:status?"
  ],
  "radar": [
    {
      "source": [
        "m.air-level.com/rank/:status",
        "m.air-level.com/rank"
      ],
      "target": "/rank/:status"
    }
  ]
}
```
