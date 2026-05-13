# 北京师范大学 - Unknown

## Coverage
`index-only`

## Route
- Namespace: `bnu`
- Namespace Name: `北京师范大学`
- Route Path: `/lib/:category?`
- Route Name: `Unknown`
- Example: `_None_`
- URL: `bs.bnu.edu.cn`
- Language: `zh-CN`
- Categories: `None`
- Maintainers: `TonyRL`
- Source Location: `lib.ts`
- Source Module: `() => import('@/routes/bnu/lib.ts')`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.lib.bnu.edu.cn/:category/index.htm`
- `target`: `/lib/:category`

## Raw JSON
```json
{
  "location": "lib.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/bnu/lib.ts')",
  "name": "Unknown",
  "path": "/lib/:category?",
  "radar": [
    {
      "source": [
        "www.lib.bnu.edu.cn/:category/index.htm"
      ],
      "target": "/lib/:category"
    }
  ]
}
```
