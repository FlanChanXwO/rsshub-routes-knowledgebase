# Air-Level - 空气质量

## Coverage
`index-only`

## Route
- Namespace: `air-level`
- Namespace Name: `Air-Level`
- Route Path: `/air/:area`
- Route Name: `空气质量`
- Example: `/air-level/air/xian`
- URL: `air-level.com`
- Language: `zh-CN`
- Categories: `forecast`
- Maintainers: `lifetraveler`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/air-level/index.ts')`

## Description
_None_

## Parameters
- `area`: 地区


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `m.air-level.com/air/:area/`
- `target`: `/air/:area`

## Raw JSON
```json
{
  "example": "/air-level/air/xian",
  "location": "index.ts",
  "maintainers": [
    "lifetraveler"
  ],
  "module": "() => import('@/routes/air-level/index.ts')",
  "name": "空气质量",
  "parameters": {
    "area": "地区"
  },
  "path": "/air/:area",
  "radar": [
    {
      "source": [
        "m.air-level.com/air/:area/"
      ],
      "target": "/air/:area"
    }
  ]
}
```
