# 新京报 - 分类

## Coverage
`index-only`

## Route
- Namespace: `bjnews`
- Namespace Name: `新京报`
- Route Path: `/cat/:cat`
- Route Name: `分类`
- Example: `/bjnews/cat/depth`
- URL: `www.bjnews.com.cn`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `dzx-dzx`
- Source Location: `cat.ts`
- Source Module: `() => import('@/routes/bjnews/cat.ts')`

## Description
_None_

## Parameters
- `cat`: 分类, 可从URL中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.bjnews.com.cn/:cat`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/bjnews/cat/depth",
  "features": {},
  "location": "cat.ts",
  "maintainers": [
    "dzx-dzx"
  ],
  "module": "() => import('@/routes/bjnews/cat.ts')",
  "name": "分类",
  "parameters": {
    "cat": "分类, 可从URL中找到"
  },
  "path": "/cat/:cat",
  "radar": [
    {
      "source": [
        "www.bjnews.com.cn/:cat"
      ]
    }
  ],
  "url": "www.bjnews.com.cn"
}
```
