# 求是网 - 在线读刊

## Coverage
`index-only`

## Route
- Namespace: `qstheory`
- Namespace Name: `求是网`
- Route Path: `/magazine/:magazine`
- Route Name: `在线读刊`
- Example: `/qstheory/magazine/qs`
- URL: `www.qstheory.cn`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `TonyRL, cscnk52`
- Source Location: `magazine.ts`
- Source Module: `() => import('@/routes/qstheory/magazine.ts')`

## Description
_None_

## Parameters
- `magazine`: 刊物，`qs` 为求是，`hqwglist` 为红旗文稿


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.qstheory.cn/:magazine/mulu.htm`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/qstheory/magazine/qs",
  "location": "magazine.ts",
  "maintainers": [
    "TonyRL",
    "cscnk52"
  ],
  "module": "() => import('@/routes/qstheory/magazine.ts')",
  "name": "在线读刊",
  "parameters": {
    "magazine": "刊物，`qs` 为求是，`hqwglist` 为红旗文稿"
  },
  "path": "/magazine/:magazine",
  "radar": [
    {
      "source": [
        "www.qstheory.cn/:magazine/mulu.htm"
      ]
    }
  ]
}
```
