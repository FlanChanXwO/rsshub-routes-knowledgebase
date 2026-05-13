# Taiwan FactCheck Center - 分類

## Coverage
`index-only`

## Route
- Namespace: `tfc-taiwan`
- Namespace Name: `Taiwan FactCheck Center`
- Route Path: `/category/:category`
- Route Name: `分類`
- Example: `/tfc-taiwan/category/weekly-top-ten-rumors`
- URL: `tfc-taiwan.org.tw/category/rumor-mill/`
- Language: `zh-TW`
- Categories: `None`
- Maintainers: `TonyRL`
- Source Location: `category.ts`
- Source Module: `() => import('@/routes/tfc-taiwan/category.ts')`

## Description
| 謠言風向球 | 議題觀察室        | TOP10                 | 名家專欄       | 國際視野             |
| ---------- | ----------------- | --------------------- | -------------- | -------------------- |
| rumor-mill | issue-observatory | weekly-top-ten-rumors | expert-columns | research-and-updates |

## Parameters
- `category`: 分類，見下表，預設為 `weekly-top-ten-rumors`


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "description": "| 謠言風向球 | 議題觀察室        | TOP10                 | 名家專欄       | 國際視野             |\n| ---------- | ----------------- | --------------------- | -------------- | -------------------- |\n| rumor-mill | issue-observatory | weekly-top-ten-rumors | expert-columns | research-and-updates |",
  "example": "/tfc-taiwan/category/weekly-top-ten-rumors",
  "location": "category.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/tfc-taiwan/category.ts')",
  "name": "分類",
  "parameters": {
    "category": "分類，見下表，預設為 `weekly-top-ten-rumors`"
  },
  "path": "/category/:category",
  "url": "tfc-taiwan.org.tw/category/rumor-mill/"
}
```
