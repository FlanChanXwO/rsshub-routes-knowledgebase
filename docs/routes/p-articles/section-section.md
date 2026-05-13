# 虚词 - 版块

## Coverage
`index-only`

## Route
- Namespace: `p-articles`
- Namespace Name: `虚词`
- Route Path: `/section/:section`
- Route Name: `版块`
- Example: `/p-articles/section/critics`
- URL: `p-articles.com`
- Language: `en`
- Categories: `reading`
- Maintainers: `Insomnia1437`
- Source Location: `section.ts`
- Source Module: `() => import('@/routes/p-articles/section.ts')`

## Description
_None_

## Parameters
- `section`: 版块名称, 可在对应版块 URL 中找到, 子版块链接用`-`连接


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `p-articles.com/:section/`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/p-articles/section/critics",
  "location": "section.ts",
  "maintainers": [
    "Insomnia1437"
  ],
  "module": "() => import('@/routes/p-articles/section.ts')",
  "name": "版块",
  "parameters": {
    "section": "版块名称, 可在对应版块 URL 中找到, 子版块链接用`-`连接"
  },
  "path": "/section/:section",
  "radar": [
    {
      "source": [
        "p-articles.com/:section/"
      ]
    }
  ]
}
```
