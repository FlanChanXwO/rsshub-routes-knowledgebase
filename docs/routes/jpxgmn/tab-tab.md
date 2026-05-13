# 极品性感美女 - 分类

## Coverage
`index-only`

## Route
- Namespace: `jpxgmn`
- Namespace Name: `极品性感美女`
- Route Path: `/tab/:tab?`
- Route Name: `分类`
- Example: `/jpxgmn/tab`
- URL: `www.jpxgmn.com`
- Language: `zh-CN`
- Categories: `picture`
- Maintainers: `Urabartin`
- Source Location: `tab.ts`
- Source Module: `() => import('@/routes/jpxgmn/tab.ts')`

## Description
_None_

## Parameters
- `tab`: 分类，默认为`top`，包括`top`、`new`、`hot`，以及[源网站](http://www.jpxgmn.com/)所包含的其他相对路径，比如`Xiuren`、`XiaoYu`等


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `mei5.vip/:tab`
- `target`: `/:tab`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/jpxgmn/tab",
  "features": {
    "nsfw": true
  },
  "location": "tab.ts",
  "maintainers": [
    "Urabartin"
  ],
  "module": "() => import('@/routes/jpxgmn/tab.ts')",
  "name": "分类",
  "parameters": {
    "tab": "分类，默认为`top`，包括`top`、`new`、`hot`，以及[源网站](http://www.jpxgmn.com/)所包含的其他相对路径，比如`Xiuren`、`XiaoYu`等"
  },
  "path": "/tab/:tab?",
  "radar": [
    {
      "source": [
        "mei5.vip/:tab"
      ],
      "target": "/:tab"
    }
  ]
}
```
