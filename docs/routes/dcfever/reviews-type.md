# DCFever - 測試報告

## Coverage
`index-only`

## Route
- Namespace: `dcfever`
- Namespace Name: `DCFever`
- Route Path: `/reviews/:type?`
- Route Name: `測試報告`
- Example: `/dcfever/reviews/cameras`
- URL: `dcfever.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `reviews.ts`
- Source Module: `() => import('@/routes/dcfever/reviews.ts')`

## Description
| 相機及鏡頭 | 手機平板 | 試車報告 |
| ---------- | -------- | -------- |
| cameras    | phones   | cars     |

## Parameters
- `type`: 分類，預設為 `cameras`


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `dcfever.com/:type/reviews.php`
- `target`: `/reviews/:type`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 相機及鏡頭 | 手機平板 | 試車報告 |\n| ---------- | -------- | -------- |\n| cameras    | phones   | cars     |",
  "example": "/dcfever/reviews/cameras",
  "location": "reviews.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/dcfever/reviews.ts')",
  "name": "測試報告",
  "parameters": {
    "type": "分類，預設為 `cameras`"
  },
  "path": "/reviews/:type?",
  "radar": [
    {
      "source": [
        "dcfever.com/:type/reviews.php"
      ],
      "target": "/reviews/:type"
    }
  ]
}
```
