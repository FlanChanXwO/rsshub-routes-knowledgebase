# 新京报 - 分类

## Coverage
`index-only`

## Route
- Namespace: `bjnews`
- Namespace Name: `新京报`
- Route Path: `/column/:column`
- Route Name: `分类`
- Example: `/bjnews/column/204`
- URL: `www.bjnews.com.cn`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `dzx-dzx`
- Source Location: `column.ts`
- Source Module: `() => import('@/routes/bjnews/column.ts')`

## Description
_None_

## Parameters
- `column`: 栏目ID, 可从手机版网页URL中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `m.bjnews.com.cn/column/:column.htm`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/bjnews/column/204",
  "features": {},
  "location": "column.ts",
  "maintainers": [
    "dzx-dzx"
  ],
  "module": "() => import('@/routes/bjnews/column.ts')",
  "name": "分类",
  "parameters": {
    "column": "栏目ID, 可从手机版网页URL中找到"
  },
  "path": "/column/:column",
  "radar": [
    {
      "source": [
        "m.bjnews.com.cn/column/:column.htm"
      ]
    }
  ],
  "url": "www.bjnews.com.cn"
}
```
