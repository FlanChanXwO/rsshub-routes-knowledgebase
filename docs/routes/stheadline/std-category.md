# 星島日報 - 即時

## Coverage
`index-only`

## Route
- Namespace: `stheadline`
- Namespace Name: `星島日報`
- Route Path: `/std/:category{.+}?`
- Route Name: `即時`
- Example: `/stheadline/std/realtimenews`
- URL: `std.stheadline.com`
- Language: `zh-TW`
- Categories: `None`
- Maintainers: `TonyRL`
- Source Location: `std/realtime.ts`
- Source Module: `() => import('@/routes/stheadline/std/realtime.ts')`

## Description
_None_

## Parameters
- `category`: 分類路徑，URL 中 `www.stheadline.com/` 後至中文分類名前部分，預設為 `realtimenews`


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.stheadline.com/theme/:category/chineseCategory`
  - `www.stheadline.com/:category/:chineseCategory`
- `target`: `/std/:category`

## Raw JSON
```json
{
  "example": "/stheadline/std/realtimenews",
  "location": "std/realtime.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/stheadline/std/realtime.ts')",
  "name": "即時",
  "parameters": {
    "category": "分類路徑，URL 中 `www.stheadline.com/` 後至中文分類名前部分，預設為 `realtimenews`"
  },
  "path": "/std/:category{.+}?",
  "radar": [
    {
      "source": [
        "www.stheadline.com/theme/:category/chineseCategory",
        "www.stheadline.com/:category/:chineseCategory"
      ],
      "target": "/std/:category"
    }
  ]
}
```
