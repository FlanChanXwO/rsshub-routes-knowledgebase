# DCFever - 二手市集 - 物品搜尋

## Coverage
`index-only`

## Route
- Namespace: `dcfever`
- Namespace Name: `DCFever`
- Route Path: `/trading/search/:keyword/:mainCat?`
- Route Name: `二手市集 - 物品搜尋`
- Example: `/dcfever/trading/search/Sony`
- URL: `dcfever.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `trading-search.ts`
- Source Module: `() => import('@/routes/dcfever/trading-search.ts')`

## Description
_None_

## Parameters
- `keyword`: 關鍵字
- `mainCat`: 主要分類 ID，見上表


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/dcfever/trading/search/Sony",
  "location": "trading-search.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/dcfever/trading-search.ts')",
  "name": "二手市集 - 物品搜尋",
  "parameters": {
    "keyword": "關鍵字",
    "mainCat": "主要分類 ID，見上表"
  },
  "path": "/trading/search/:keyword/:mainCat?"
}
```
