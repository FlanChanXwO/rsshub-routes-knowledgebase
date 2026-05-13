# 台視新聞網 - 分类

## Coverage
`index-only`

## Route
- Namespace: `ttv`
- Namespace Name: `台視新聞網`
- Route Path: `/:category?`
- Route Name: `分类`
- Example: `/ttv`
- URL: `news.ttv.com.tw`
- Language: `zh-TW`
- Categories: `traditional-media`
- Maintainers: `dzx-dzx`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/ttv/index.ts')`

## Description
_None_

## Parameters
- `category`: 分类


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `news.ttv.com.tw/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/ttv",
  "location": "index.ts",
  "maintainers": [
    "dzx-dzx"
  ],
  "module": "() => import('@/routes/ttv/index.ts')",
  "name": "分类",
  "parameters": {
    "category": "分类"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "news.ttv.com.tw/:category"
      ]
    }
  ]
}
```
