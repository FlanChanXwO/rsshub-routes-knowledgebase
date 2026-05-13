# 鏡週刊 Mirror Media - 分类

## Coverage
`index-only`

## Route
- Namespace: `mirrormedia`
- Namespace Name: `鏡週刊 Mirror Media`
- Route Path: `/category/:category`
- Route Name: `分类`
- Example: `/mirrormedia/category/political`
- URL: `mirrormedia.mg`
- Language: `zh-TW`
- Categories: `traditional-media`
- Maintainers: `dzx-dzx`
- Source Location: `category.ts`
- Source Module: `() => import('@/routes/mirrormedia/category.ts')`

## Description
_None_

## Parameters
- `category`: 分类名
- `section`: 子板名


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `mirrormedia.mg/category/:category`
  - `mirrormedia.mg/section/:section`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/mirrormedia/category/political",
  "location": "category.ts",
  "maintainers": [
    "dzx-dzx"
  ],
  "module": "() => import('@/routes/mirrormedia/category.ts')",
  "name": "分类",
  "parameters": {
    "category": "分类名",
    "section": "子板名"
  },
  "path": [
    "/category/:category",
    "/section/:section"
  ],
  "radar": [
    {
      "source": [
        "mirrormedia.mg/category/:category",
        "mirrormedia.mg/section/:section"
      ]
    }
  ]
}
```
